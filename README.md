# Replica Set Example from The Kubernetes Book
This example is used to illustrate the ability of Kubernetes to scale through
the use of manifest files.  The rs.yaml manifest file will create 10 Pods by default, each one running a nigelpoulton image.  The svc.yaml file will create a service for the replica set to run under.  The deploy.yaml file will create a deployment that can create a new replica set, connect to the pods, and be used for rolling updates
