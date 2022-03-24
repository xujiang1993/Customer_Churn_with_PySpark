# Customer_Churn_with_PySpark

Streaming media companies such as Sportify and Tencent Music are easily to join or cancel service which results in customer churn (customer stop using the service or product). If we can predict in advance that the customer will churn, we can take actions such as sending coupons to retain the customer in advance. This project will use PySpark to predict customer churn.

# Data
The data of this work is provided by Udacity. Since this demo only work locally, I choose a relatively small data subset (128MB) for this work (the full dataset would be 12GB). The data used in this blog contains the records of the customer behaviors( e.g. Add Friend, Add to Playlist, Next Song, Roll Advert, Thubs Down and Thumbs up etc), the details of the songs, artists, login devices and events timestamps.An snapshot of the records is given below.
![This is snapshot of data](pic/data.GIF)
The snapshot of the dataEach row of the data represent an user operation log and the timestamps can help us to sort the events.

# Package Requirement
The code was developed on python 3. The following packages are required:
* pyspark


# Licensing, Authors, Acknowledgements
I would like to thank Udacity for this amazing project
