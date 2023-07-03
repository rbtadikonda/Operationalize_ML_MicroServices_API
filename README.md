[![CircleCI](https://circleci.com/gh/rbtadikonda/Operationalize_ML_Microservices_API.svg?style=svg)](https://circleci.com/gh/rbtadikonda/Operationalize_ML_Microservices_API)

## Project Overview

In this project, I applied the skills that were acquired to operationalize a Machine Learning Microservice API using containerization and kubernetes orchestration concepts


## Steps Followed
### Setting up the Environment

* Created a virtualenv with Python 3.7 and activated it. 
```bash
python3 -m venv ~/.devops
source ~/.devops/bin/activate
```
* updated requirements.txt with appropriate version for recent upgrades
* Ran `make install` to install the necessary dependencies
* lint was done against make file and was updated to accomodate for latest upgrades

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Docker setup and configuration was done locally
* Kubernetes setup and configuration was done locally
* Created Flask app in Container
* Ran the app via kubectl
