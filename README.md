Liu Longyin
Sharon Mariam Mathew A0113000N  
Nguyen Cao Nhat Linh


Overview of solution

For this assignment, we have used a combination of the accelerometer and the magnetometer to detect the direction 
and the range to produce the appropriate gunshot. Using the upper threshold and the lower threshold, 
we check if the accelerometer has finished oscillating from the top threshold near the top of the peak to 
the bottom threshold and when that occurs, we generate the gunshot. We had also altered the variable MIN_ACCL_FORCE 
from 7.0F to 10.F as we observed that the frequency of the gunshots were higher at 10.0F more so than 7.0F. 
