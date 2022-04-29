# Real World Kubernetes: Observe, Monitor, and Alert

This repo contains the resources for the Kubernetes class I teach that helps you understand what in the world is actually happening on your cluster. 

## Overview

🔭 This three hour action packed class is one giant demo of working code that you can use in your own environment.  We use a sample python application that is running on our kubernetes cluster and add monitoring, observabilty, and alerting so we can really understand the details of our cluster. 
In this class we cover: 

* Kubernetes GUI options including Lens and k9s. 
* Prometheus for gathering metrics
* Grafana Dashboards
* Alerting with Grafana metrics 
* Integration with Slack
* CloudWatch Alerts
* The FEK stack
* FluentD (td-agent) 
* LogServer (td-agent to files)
* Terraform ElasticSearch (OpenSearch)
* Session Logging 
* Searching Logs in Kibana

## Modules

We start with an EKS cluster generated with Terraform. 

* Module 0: Introduction 
	* Terraform EKS cluster

* Module 1: Basic GUI tools
	* Metrics Server
	* Lens
	* k9s
	
* Module 2: Application Overview
	* Install basic application running on cluster. 
	* Add slack metrics for key events. 

* Module 3: Prometheus
	* Installing and configuring Prometheus
	* Exploring Prometheus
	
* Module 4: Grafana
	* Installing and configuring Grafana
	* Integrating Prometheus with Grafana
	
* Module 5: Prometheus Metrics in your Application
	* Adding metrics and counters to your application. 
	* View metrics and counters in Grafana
	
* Module 6: CloudWatch Alerts
	* Alerts for your cluster with CloudWatch with Terraform. 
	* Integration with Slack
	
* Module 7: The FEK stack
	* Installing and configuring Fluentd (td-agent)
	* Terraform Install a log server
	* Terraform install ElasticSearch and Kibana
	* Add logging to your application 
	* Using Sessions in your application for better log tracing. 
	* Exploring Logs on Kibana

* Module 8: Conclusion
	* Where to get more help
	* Where to go next
	* Further resources

