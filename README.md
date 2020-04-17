# [Plot](https://i.imgur.com/n0CFhUg.gifv)

*Variance* is a measure of how much a data set varies. It is found by taking the distance from each data point to the mean, squaring it, and then finding the average size of all those squares. 

In this plot, the variance of the X data would be the average size of the blue squares, and the variance of the Y data is the average size of the purple squares.

*Covariance* is a similar measurement that describes how much *two* sets of data vary with each other. But instead of looking at squares, we look at the rectangles formed with one side being the distance to the X mean and the other side being the distance from the Y mean. Covariance is the average area of all of these rectangles. Keep in mind that some rectangles will have negative areas if one side is less than the mean.

The variance of two data sets added together, VAR(X + Y), is unfortunately not equal to VAR(X) + VAR(Y) but instead equal to VAR(X) + VAR(Y) + 2COV(X, Y)
