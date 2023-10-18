# weatherman
website for registering and handling weather updates 

from [Gwyneth Peña-Siguenza](https://github.com/madebygps/projects/tree/main/az-204#1-weather-tracker-develop-azure-compute-solutions)

#### Weather Tracker (Develop Azure compute solutions)
A web application that allows users to track weather updates in real-time for their chosen cities. The system also triggers Azure Functions for alerts when a specific weather threshold is met (like if it's going to rain).

Infrastructure
- [Azure App Service Web App (Hosting the web application)](#webapp)
- [Azure Container Registry (Storing Docker images for the app)](#containerregisty)
- Azure Container Instance (Running the containers for development/testing)
- Azure Functions (Weather alert system)
- Azure Container Apps (Running the containers in production)

Diagram
![image](https://github.com/raketjan/weatherman/assets/124059/90a88c77-95d3-46b1-83a8-973275862f57)

### Implementation Guide
- [ ] Create an Azure App Service Web App.
- [ ] Develop a basic web application that uses weather APIs.
- [ ] Containerize the application.
- [ ] Publish the container image to Azure Container Registry.
- [ ] Test the application using Azure Container Instance.
- [ ] Implement an Azure Function to send alerts when a specified weather threshold is met.
- [ ] Integrate Azure Function with your web application.
- [ ] Deploy the web application to Azure Container Apps.
- [ ] Setup a CI/CD pipeline for your application and Function.
- [ ] Setup Application insights and Azure monitor
- [ ] Push to GitHub
Document



### Blazor webapp <a name="webapp"></a>

  
    - [ ] Finish Blazor Learn module
    - [ ] Implement a basic website containing the required fields/functionality
    ##### Optional
    - [ ] Set up Github Actions to build/release when pushed to repo
    - [ ] Set up Github Actions to let Azure build/release when pushed to repo

### Azure Container Registry (Storing Docker images for the app)<a name="containerregistry"></a>

