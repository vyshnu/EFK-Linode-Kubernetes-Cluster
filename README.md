# EFK-Linode-Kubernetes-Cluster

This repository project is based on Nana Janashia 's Udemy's course "logging-in-kubernetes-with-efk-stack" with minor changes.

This project basically has logs from the java app and node app captured by fluentd.Fluentd processes the logs and sends it the elasticsearch store and can be visualised using the kibana.The entire cluster is setup in Linode Kubernetes engine(LKE).

### Set up elastic stack in kubernetes cluster (EFK) Elastic - FluentD - Kibana

<img src="https://techtiefen.de/podlove/image/68747470733a2f2f7465636874696566656e2e64652f77702d636f6e74656e742f75706c6f6164732f656c61737469632e706e67/500/500/0/elasticsearch" width="40px" height="40px" />

<img src="https://pbs.twimg.com/profile_images/765159101542244353/Sgj58-zy_400x400.jpg" width="40px" height="40px" />

<img src="https://img.stackshare.io/service/1722/Image_2019-05-20_at_4.53.31_PM.png" width="40px" height="40px" />

##### - Set up docker hub private repository to push java and node app images

##### - Create k8s cluster on Linode LKE

##### - Deploy k8s dashboard in the cluster

##### - Deploy node and java app images in the cluster

##### - Deploy ElasticSearch with helm 

##### - Deploy Kibana with helm 

##### - Deploy FluentD with helm 

##### - Configure FluentD to process container logs and send them to elastic 
