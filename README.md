# Page View Time Series Visualizer

This is the boilerplate for the Page View Time Series Visualizer project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/page-view-time-series-visualizer

# Attribution
KM, 10.06.2024:

I had massive issues getting the tests working. At the end it turned out it was an issue with my Seaborn version. For debbuging purposes I searched for others' solutions and found one which I used as a reference for getting the tests working. 

https://github.com/fuzzyray/page-view-time-series-visualizer.git

This helped me to figure oute that I needed to upgade from Seaborn v0.12.2 to 0.13.

My final code looks similar to the one from fuzzyray but I used a different method to "inject" the missing month's data into the dataframe. I further need to add some hacks for getting the x-ticks in a format to pass the tests in test_module.py
