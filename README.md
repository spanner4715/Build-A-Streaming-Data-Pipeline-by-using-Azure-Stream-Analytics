# Build-A-Streaming-Data-Pipeline-by-using-Azure-Stream-Analytics  
![image](https://user-images.githubusercontent.com/103509243/201195498-14b7b857-7417-469d-b83f-b56a9ddaa666.png)


## Approach    
(1) Create an Azure event hub.  

(2) Create an Azure stream analytics job.  

(3) Create an Azure SQL database.  

(4) Create table structure (Dataset) in SQL database.  

(5) Add the event hub as an input source for the stream analytics job  

(6) Add the azure SQL database as the output source for the stream analytics job   

(7) Start stream analytics job.

(8) Run python script, which can send streaming data from the Event hub into the azure SQL database.  

(9) Load data from azure SQL database tables into Power BI.  

(10) Create a dashboard in Power BI.

### Notification
(1) Connection_str (in transport_index.py)
![image](https://user-images.githubusercontent.com/103509243/201256024-c036d79d-58e4-44be-aa56-917d78b191be.png)
(2) Connection to SQL database
![image](https://user-images.githubusercontent.com/103509243/201256515-971b08ff-03ee-4c6a-b50d-130ba617eeae.png)
(3) Set up firewall
![image](https://user-images.githubusercontent.com/103509243/201256554-e009f27c-36dc-49a1-a054-0f12bd8b0e44.png)

