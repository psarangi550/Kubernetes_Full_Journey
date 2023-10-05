# History of Container Orchestration

- `How docker change the world with containerization`

- `How kubernetes emerged as container orchestration tool for managing container at scale`

- `Docker first starts with doccloud` which `create, package and distribute application as containers`

- `it will be a simple way to manage dependency and configuration `

- from `different programing language`  can `build their application ` and `package it into` the `container`  and `deploy to anywahere` i.e from the `laptop to a data center`

- this will help in `develop and deploy the application without the dependency hell ` which can occure `traditional software development process`

- all the `depedency will become a part of the container image` and hence we don't have to worry about the `operating system related configuration`

- when the popularity gain happended for `docker` there is also a problem occure `How to run container at scale`

- by that time `container orchestrator war` happend between `multiple container orchestrator company`
  
  -  `Nomad from Hashigroup`
  
  - `openshift`
  
  - `docker-swarm`
  
  - `kubernetes`

- `kubernetes` become the `leading container orchestration tool`

- some of them such as `openshift` uses the `kubernetes as the backend engine`

- **kubernetes**
  
  - `kubernetes` is a `container orchestrator` for running `container on mass`
  
  - it is developed by `google` and released as a `opensource project in 2014` , `Feb 2015 kubernetes 1.0 been releaed` which is considered as `steady for production`
  
  -  `kubernetes` `provide means to` 
     
     -  `automate deployment` 
     
     -  `Scaling` 
     
     -  `management of the containerized application`   

  
  - `kubernetes` run as `cluster of nodes` , where the `cluster` being small as the `one node` or can scale upto `thousands of nodes`
  
  - where the `cluster are running the containerized application`
  
  - in addition to `manage containers` , `kubernetes can provide the tools for monitoring  and logging `
  
  - `moniting and logging` are `important` when we are running the `containerized application` in an `distributed platform`   
  
  
  - `Kubernetes` has the `functionality` for 
    
    - `automatic scaling`
      
      - where `kubernetes` can handled `no of container running on demand` 
    
    - `self healing`
      
      - with the `self healing` we can `restart the container` which is `getting failed` 
  
  - in the old days we need to build the `infrastructure scafolding around the application for support`
  
  - with `kubernetes` we `get` `almost all things we need to run the application`   
  
    - `configuration manangement`
    
    - `managing secret`
    
    - `high availability`
    
    - `scaling`   

    - `automated deployments`



-  with `Docker` we can `easily package and distribute application as container `

- with `kubernetes` took this to the `next level` as a `toolset` for `managing` `container at scale`
  


