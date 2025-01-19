
![application-dashboard](https://github.com/user-attachments/assets/89e96928-ee9a-4f38-aa5f-411fdf67b8b8)

# CI/CD Workflow for Automated Static Website Deployment 🚀

### 1️⃣ Developer Pushes Code
Developers push code changes to the **GitHub repository**, initiating the **CI/CD pipeline**. This begins the automation process for deploying the application to production.

- ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

### 2️⃣ CodePipeline Source Stage
When code is pushed to the GitHub repository, the **AWS CodePipeline source stage** detects changes and triggers the pipeline. CodePipeline automates the build, test, and deployment phases.

- ![AWS CodePipeline](https://img.shields.io/badge/AWS%20CodePipeline-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

---

### 3️⃣ CodeDeploy Deployment
Once the changes are detected, **AWS CodeDeploy** is responsible for deploying the application to **Amazon S3**. CodeDeploy facilitates smooth and reliable deployments, ensuring application updates reach production without manual intervention.

- ![AWS CodeDeploy](https://img.shields.io/badge/AWS%20CodeDeploy-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

---

### 4️⃣ S3 Storage
The application is stored in **Amazon S3** as static website content. **S3** provides scalable, secure, and highly available storage for the deployed application, enabling the website to be reliably delivered to users.

- ![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

---

### 🚀 CI/CD Workflow Overview:
This streamlined **CI/CD pipeline** ensures efficient delivery of code changes to production while maintaining **reliability**, **scalability**, and **automation** in the deployment process.

- **Efficient Automation**: Developers push code, triggering an automatic pipeline that deploys directly to production.
- **Reliability**: AWS services like CodePipeline and CodeDeploy ensure that the application is deployed with minimal downtime and errors.
- **Scalability**: Amazon S3 ensures that your static website content is highly available and can scale to meet user demand.

### 📊 Benefits:
- **Automation of Code Deployment**: No manual intervention is needed once the pipeline is set up.
- **Reliability**: Continuous deployment and monitoring ensure that changes are deployed quickly with no disruption.
- **Scalability**: S3 and AWS services scale automatically to meet traffic demands.
