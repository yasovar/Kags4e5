Documentation

Non-Linear Scaling

All the variables have a near normal distribution.

Need to scale this according such that values near mean are scaled much more than
values further away from the mean.
For this we need a function which:
1. always increases
2. positive slope that converges to same value at +ve and -ve infinity
3. highest values of slope at mean

Used a tanh function:
std*tanh(x-mean)


Model used for training:
XGB