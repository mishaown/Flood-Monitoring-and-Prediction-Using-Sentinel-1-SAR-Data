# Flood-Monitoring-and-Prediction-Using-Sentinel-1-SAR-Data

Hey there! 👋 Welcome to this project that uses satellite data to monitor and predict floods. We're working with Sentinel-1 SAR data from the European Space Agency (ESA), and the goal here is to help track floods and maybe even predict when they’re likely to happen.
What’s this project about?

In simple terms, we use radar images (from satellites) to identify flooded areas, map the extent of the flood, and even try to predict future flood events based on past data.
What we did here:

    Data Acquisition
    First, we grab some cool data from the ESA's Copernicus Hub. These are radar images from the Sentinel-1 satellite that capture areas affected by floods.

    Preprocessing the data
    Before we dive into analyzing, we clean the data a bit. We apply some filtering to remove noise (because who wants that?) and convert the raw data into something usable.

    NDWI Analysis
    Here’s where the magic happens. We calculate something called NDWI (Normalized Difference Water Index). This helps us find water bodies before, during, and after the flood.

    Flood Mapping
    By comparing water levels from different time periods, we can create maps showing the areas that got flooded. You’ll end up with a pretty clear view of the flood extent.

    Time Series Analysis
    We go a step further by analyzing changes in water levels over time. This is how we try to predict future floods. Trends = more insight.

    Accuracy Check
    Of course, we don't just trust the computer blindly. We compare the flood maps with actual ground data and other high-quality images to make sure we’re getting it right.

This project's dataset is available for download at the following site: 
(https://sentinel.esa.int/web/sentinel/user-guides/sentinel-1-sar/data-products).

Future Plans

    Improve the prediction model for more accurate flood forecasting.
    Experiment with other datasets (like PM2.5 or AOD) to monitor more environmental factors.

Contributions

Feel free to fork the repo, open issues, or submit pull requests. Let’s improve this project together!
