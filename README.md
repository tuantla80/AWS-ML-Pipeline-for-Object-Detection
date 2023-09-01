### AWS Setup
- Setting up IAM User
- Setting up AWS Sagemaker:
  - It is charged: use appropiate instance type to save money.
### Dataset  
- [Google Open Images Dataset](https://storage.googleapis.com/openimages/web/index.html)
- Using Plastic bag images for this project.
### [Exploratory Data Analysis on Sagemaker](https://github.com/tuantla80/AWS-ML-Pipeline-for-Object-Detection/blob/main/Object%20Detection%20-%20Exploratory%20Data%20Analysis%20(EDA).ipynb)  
- Exploratory Data Analysis (EDA)
- Splitting data
- Data Engineering with Mxnet RecordIO format
- Note: Use instance ml.t2.2xlarge on Sagemaker
### [Data Augmentation](https://github.com/tuantla80/AWS-ML-Pipeline-for-Object-Detection/blob/main/Data%20Augmentation.ipynb)  
- Flip Left Right: Image and its bounding boxes
- Veryfing data before and after augmentation
### [Setting up and Creating Training Job](https://github.com/tuantla80/AWS-ML-Pipeline-for-Object-Detection/blob/main/Seeting%20up%20and%20Creating%20Training%20Job.ipynb)  
- Create RecordIO file and upload to AWS S3
- Download Object Detection Algo and Setting up Estimator Object
### [Analysing training job results](https://github.com/tuantla80/AWS-ML-Pipeline-for-Object-Detection/blob/main/Analysing%20Training%20Job%20results.ipynb)  
- Deploying model in Sagemaker notebook
- Visualizing inference results and testing endpoints
### [Inference: Setting up Batch Transformation](https://github.com/tuantla80/AWS-ML-Pipeline-for-Object-Detection/blob/main/Setting%20up%20Batch%20Transformation.ipynb)  
- Analysing batch transformation job
- Visualizing batch transformation results
###
   
