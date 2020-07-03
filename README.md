# os-sample-java-web
Sample Java Web Application for use in OpenShift


oc new-app jboss-webserver31-tomcat8-openshift:1.2~https://github.com/OpenShiftDemos/os-sample-java-web.git --name sample-java-web
oc expose svc/sample-java-web
