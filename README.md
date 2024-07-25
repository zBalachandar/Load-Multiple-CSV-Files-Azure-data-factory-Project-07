# Load-Multiple-CSV-Files-Azure-data-factory-Project
How to Load Multiple CSV Files  in Azure Data Factory - Azure Data Factory Tutorial. In this Project, you will learn how to load multiple csv files from blob storage to another target location.
<div align="center">
  <a href="#">
    <img src="https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/AZURE%20PORTAL.png" alt="Banner" width="720">
  </a>

  <div id="user-content-toc">
   
  </div>
  
  <p>Load-Multiple-CSV-Files-Azure-data-factory-Project</p>
</div>
<br>


<a name="introduction"></a>
## 🔬 Project Overview
In this project we are going to do one end to end azure data engineer project and understand how to Load Multiple CSV Files  in Azure Data Factory - Azure Data Factory Tutorial. In this Project, you will learn how to load multiple csv files from blob storage to another target location.

### 💾 Dataset
Dataset : https://drive.google.com/drive/folders/1lqV6h0l8qqoOlIryRhJvVVc1eHmu-bmu

### Business Requirement.
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/Business%20Requirement.jpg)

### Project steps to follow: 

There are different methods for incremental data loading. I will discuss the step-by-step process for incremental loading, or delta loading

1.Prepare the source data and store it in blob storage container as input .
2.Create a data factory.
3.Create linked services.
4.Create source, sink, and change tracking datasets.
5.Create, run, and monitor the full copy pipeline.
6.Check the output container for files.

In this project we are going to do one end to end azure data engineer project and understand how to Load Multiple CSV Files in Azure Data Factory . In this Project, you will learn how to load multiple csv files from blob storage to another target location.

### ⚙️ Data Loading
 Data Loading by using in Azure Data Factory Environment.
 1.Prepare the source data store.
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/AZURE%20PORTAL.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/blob%20Storage%20ac%20overview.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/Input%20container.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/output%20container%200.png)

2.Create a data factory.
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/data%20factory%20ov1.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/source%20dfy1.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/source%20dfy2c.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/sink%20json%20s.png)

3.Create linked services.
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/sink%20json%20se.png)

4.Create source, sink, and change tracking datasets.
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/sink%20json%20s.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/source%20dfy2c.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/pipeline%20p1.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/sink%20json%20s.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/sink%20json%20se.png)



5.Create, run, and monitor the full copy pipeline.

![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/pipeline%20publish.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/pipeline%20triggered%20success.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/pipeline%20triggered%20success%20status.png)
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/publish%20completion.png)

6.Check the Output container for files.
![image](https://github.com/zBalachandar/Load-Multiple-CSV-Files-Azure-data-factory-Project-07/blob/4e332559b3d74b5b2ecc259762b716c6d0b9377a/Assets/results%20output%20container.png)


### 🛠️ Technologies Used

- **Data processing**: Azure Data Factory
- **Data loading**: Azure blob storage containers.

<a name="credits"></a>
## 📋 Credits

- This Project is inspired by the video of the [YouTube Channel "Learn by doing it"](https://www.youtube.com/watch?v=pMqnvXgPKlI&list=PLOlK8ytA0MghGmAAT8W2u7VYmICdzeU5t&index=1&t=96s)  

<a name="contact"></a>
## 📨 Contact Me

[LinkedIn](https://www.linkedin.com/in/balachandars2022/) •
[Gmail](balachandar2014elu@gmail.com)  •

