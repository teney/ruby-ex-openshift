# Demo of a Jenkins Pipeline on minishift

Run ```oc create -f ruby-ex-all.yaml``` to create the following:
- deploymentConfig
- buildConfig for app
- route 
- service
- imageStream

Run ```oc create -f ruby-ex-jenkins.yaml``` to create the jenkins pipeline

## Todo
Create a template to install pipeline