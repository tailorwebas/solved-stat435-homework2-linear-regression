Download Link: https://assignmentchef.com/product/solved-stat435-homework2-linear-regression
<br>
If you are not familiar with R you may want to go through Chapter 3.6: ”Lab: Linear Regression” of ISLR.

<strong>Problem 1 </strong>

In this problem, we will make use of the Auto data set, which is part of the ISLR package.

<ol>

 <li>Fit a least squares linear model to the data, in order to predict mpg using all of the other predictors except for name. Present your results in the form of a table. Be sure to indicate clearly how any qualitative variables should be interpreted. For each predictor, comment on whether you can reject the null hypothesis that there is no linear association between that predictor and gas mileage, conditional on the other predictors in the model. 2. What is the resubstitution (training) mean squared error of this model?</li>

 <li>What gas mileage do you predict for a Japanese car with three cylinders, displacement 100, horsepower of 85, weight of 3000, acceleration of 20, built in the year 1980?</li>

 <li>On average, holding all other covariates fixed, what is the difference between the mpg of a Japanese car and the mpg of an American car?</li>

 <li>On average, holding all other covariates fixed, what is the change in mpg associated with a 10-unit change in horsepower?</li>

</ol>

<strong>Problem 2 </strong>

Consider using only the origin variable to predict mpg on the Auto data set. In this problem, we will explore the coding of this qualitative variable.

<ol>

 <li>First, code the origin variable using two dummy (indicator) variables, with Japanese as the default value. Write out an equation like (3.30) in the textbook, and report the coefficient estimates. What is the predicted mpg for a Japanese car? for an American car? for a European car?</li>

 <li>Now, code the origin variable using two dummy (indicator) variables, with American as the default. Write out an equation like (3.30) in the textbook, and report the coefficient estimates. What is the predicted mpg for a Japanese car? for an American car? for a European car?</li>

</ol>

1

<ol start="3">

 <li>Now, code the origin variable using two variables that take on values of +1 or −1, as in the top of page 85 of the textbook. Write out an equation like (3.30) in the textbook, and report the coefficient estimates. What is the predicted mpg for a Japanese car? for an American car? for a European car?</li>

 <li>Finally, code the origin variable using a single variable that takes on values of 0 for Japanese, 1 for American, and 2 for European. Write out an equation like (3.30) in the textbook, and report the coefficient estimates. What is the predicted mpg for a Japanese car? for an American car? for a European car?</li>

 <li>Comment on your results in (a)-(d).</li>

</ol>

<strong>Problem </strong>

Consider using least squares linear regression to predict weight (<em>Y </em>) using height.

<ol>

 <li>Suppose that you measure height in inches (<em>X</em><sub>1</sub>), fit the model</li>

</ol>

and obtain the coefficient estimates <em>β</em><sup>ˆ</sup><sub>0 </sub>= −165<em>.</em>1 and <em>β</em><sup>ˆ</sup><sub>1 </sub>= 4<em>.</em>8. What weight will you predict for an individual who is 64 inches tall?

<ol start="2">

 <li>Now suppose that you want to measure height in feet (<em>X</em><sub>2</sub>) instead of inches. (There are 12 inches to a foot.) You fit the model</li>

</ol>

What are the coefficient estimates? What weight will you predict for an individual who is 64 inches tall (i.e. 5<em>.</em>333 feet)?

<ol start="3">

 <li>Now suppose you fit the model</li>

</ol>

which contains both height in inches and height in feet as predictors. Provide a general expression for the least squares coefficient estimates for this model.

<ol start="4">

 <li>How do the (training set) mean squared errors compare for three models fit in (a)–(c)?</li>

</ol>

2