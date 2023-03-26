# Popularity-and-Download-Prediction
The objective of the project is to solve the challenge of predicting whether a photograph is likely to be popular and generate a significant number of downloads.
The dataset containing various features of photographs such as the camera type, location, lighting conditions, and other image-specific characteristics. 
The objective is to develop a predictive model that can accurately predict the lifetime download count of an image based on these features.

About the data set
1) train.csv
The dataset provided in the train.csv consists of the following features:

* image_id: The unique ID for each data point.
* photo_url: The URL of the photograph.
* photo_image_url: The URL of the image file.
*  photo_submitted_at: The date and time when the photograph was submitted.
*  obs_day, obs_hour, obs_min, obs_sec: The day, hour, minute, and second when the photograph was observed.
*  image_category: The category of the photograph.
* width: The width of the image in pixels.
 * height: The height of the image in pixels.
 * aspect_ratio: The aspect ratio of the image.
 * description1, description2: The descriptions of the photograph.
 * camera_make: The brand of the camera used to take the photograph.
 * camera_model: The model of the camera used to take the photograph.
 * iso: The ISO value used to take the photograph.
*  aperture_value: The aperture value used to take the photograph.
*  focal_length: The focal length used to take the photograph.
*  exposure_time: The exposure time used to take the photograph.
 * latitude: The latitude of the photograph location.
 * longitude: The longitude of the photograph location.
 * country: The country where the photograph was taken.
*  city: The city where the photograph was taken.
*  total_days: The total number of days since the photograph was submitted.
*  stats_downloads: The total number of downloads for the photograph. (This is the target variable that participants will be predicting.)
2) train_keywords.csv
*  image_id: The unique ID for each data point.
*  image_classification: The classification label assigned to the image.
*  classification_keyword: The keyword used to classify the image.
*  confidence_value: The confidence value for the classification label assigned to the image.
3) train_colors.csv
*  image_id: The unique ID for each data point.
*  R, G, B: The Red, Green, and Blue values for the image.
*  image_hex: The hexadecimal code for the dominant color of the image.
*  keyword: The keyword associated with the dominant color of the image.
*  pixel_coverage: The percentage of the image covered by the dominant color.
*  color_score: The colorfulness score for the image.


## Contributing
This repository is open for contributions. If you find any issues or have any suggestions, feel free to create a pull request or open an issue.






