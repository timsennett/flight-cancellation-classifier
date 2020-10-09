
# Flight Delays and Cancellations Classifier

In this project, I've chosen to work with the [2015 Flight Delays and Cancellations](https://www.kaggle.com/usdot/flight-delays#flights.csv) dataset for the purpose of creating a binary classification model.

The notebook found in `student.ipynb` records the start-to-finish Data Science Process, from preprocessing and exploration to modeling and interpreting. Ultimately, this work aims to predict whether a flight will (1) depart at its scheduled time, or (2) be delayed or canceled.

![takeoff](https://media.giphy.com/media/l0IyoqulCpw5YqTGE/giphy.gif)


## Repositary directory

The dataset is quite large as constituted (564.96 MB), which led to my decision to work with only a subset of it, limited to three major airlines from the United States: Delta, American Airlines, and US Airways. That subset can be found in `flight_us.csv`.

A full list of features and their respective descriptions have been placed in the `columns.txt` file of this repository.

The inlcuded file `airlines.csv` provides full names of all airlines found in the original dataset, among which three are relevant to this project (AA, US, DL). This list is helpful as a means to matching each airport to its unique IATA code, as the dataset itself references airports by IATA code only.

Likewise, `airports.csv` provides full names of all airports found in the original dataset, along with each airport's IATA code.

See below for more on `presentation.pdf`.


## Executive Summary

Among the deliverables for this project is that I prepare and deliver a mock "executive summary" presentation to a hypothetical stakeholder of my choosing, describing my process and results in a non-technical manner, and making a case as to why my findings are important from a business perspective.

I've chosen to share my work with the leadership team of a mobile app development company that's creating an app for customers to know whether a given flight will be canceled or delayed—often before it's even announced by the airline—helping them to avoid wasted hours at an airport gate. The company's success hinges upon the app's ability to provide reliable, timely results to customers.

The PowerPoint slides used in this executive summary presentation are located in `presentation.pdf`.


## Blog post

Visit https://medium.com/@timsennett/converting-integers-and-floats-to-datetime-in-pandas-4e754dc978fb to read my blog post on a topic related to this project.


## Support 

Reach out to me on [LinkedIn](https://www.linkedin.com/in/timsennett/) for further support, or any feedback worth sharing.
