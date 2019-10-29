# Human-Activity-Recognition
A Classification based task of predicting human activity based on the raw sensor data from the Accelerometer and Gyroscope.

* Types of MLPs tried are,
  1. Used basic multi layered LSTM since it's a time series data of overlapping windows.
  2. Tried basic 1D Convolutions.
  3. Implemented a divide on conquer based technique of dynamic and static activity models as provided in reference-1.  

* References:
  1. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5949027/
  2. https://github.com/maxpumperla/hyperas
