# YAML-For-DevOps
This repository gives understanding of YAML and their Use cases in DevOps

# What is YAML?
* YAML (short for "YAML Ain't Markup Language") is a human-readable data serialization format that is often used for configuration files and data exchange between systems. 
* YAML is a human-readable data serialization format that is commonly used in configuration management and automation tools.
* YAML is similar to other data serialization formats like JSON and XML
* YAML is commonly used in configuration files for tools and applications, as well as in cloud infrastructure management tools like AWS CloudFormation, Kubernetes, and Ansible.

Here's an example of a simple YAML document:

```yml
name: vaibhav kapase
age: 21
email: vaibhavkapase132@gmail.com
```

YAML extension is
``` .yaml ``` or ``` .yml```

For Comment in YAML
use ``` "#" ```
Comments start with the "#" character and continue to the end of the line. 

Here's an example:
```yml
# This is a YAML comment
key: value # This is a comment at the end of a line
```

## Here's an example of YAML code used in DevOps for defining a Kubernetes deployment:
```yml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: my-app-deployment
spec:
  replicas: 3
  selector:
    matchLabels:
      app: my-app
  template:
    metadata:
      labels:
        app: my-app
    spec:
      containers:
      - name: my-app-container
        image: my-app-image:latest
        ports:
        - containerPort: 8080
```
## Basic Syntax of YAAML

Key-Value Pairs
Real life example of key value pair example:
<img src="https://github.com/vaibhavkapase1302/YAML-For-DevOps/blob/main/YAML%20key-value%20pair%20eg.png" alt="GitHub Logo" align="left" width="300" height="500" >
