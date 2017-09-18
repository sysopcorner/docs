# SysOpCorner tools
----

## Microservices


http://stratos.apache.org/about/why-apache-stratos.html
PAAS :)

https://hyper.sh/ Hypervisor-agnostic Docker engine. Make VMs run like Containers

https://stacksmith.bitnami.com/
Create custom container images in minutes via web.

https://github.com/gophergala2016/meshbird/ - istributed private networking between servers, containers, virtual machines and any computers in different datacenters, different countries, different cloud providers using DHT (Distributed Hash Table)

https://github.com/coreos/flannel/ - private networking with etcd as a peer backend

https://github.com/serverless/serverless - Serverless is the application framework for building serverless web, mobile and IoT applications (JAAWS)

https://convox.com/ - Build, deploy, and manage applications with ease (auto gen Dockerfiles based on lang detected)

http://gradle.org/ - APP build automatization tool.

https://github.com/ciscocloud/mantl - mesos with logs/monitoring, etc by cisco

##  Orchestrators
https://brooklyn.incubator.apache.org/learnmore.html
Brooklyn is built for the cloud, and will take a blueprint and deploy it to one of many supported clouds or even to multiple different clouds, or to private infrastructure (bring-your-own-node), or to other platforms. It will dynamically configure and connect all the different components of an application, e.g. so load balancers know where the web servers are and the web applications know where the database is.

https://mesosphere.github.io/marathon/
A cluster-wide init and control system for services in cgroups or Docker containers.

https://github.com/GoogleCloudPlatform/kubernetes
Kubernetes is an open source implementation of container cluster management.

https://github.com/longshoreman/longshoreman
Longshoreman automates application deployment using Docker. Just create a Docker repository (or use a service), configure the cluster using AWS or Digital Ocean (or whatever you like) and deploy applications using a Heroku-like CLI tool.

http://clocker.io/
Clocker contains Brooklyn entities, locations and examples that create a Docker cloud infrastructure

http://palletops.com/
Automates controlling and provisioning cloud server instances. DevOps for the JVM.

http://www.terraform.io/
better CloudFormation

http://dkron.io/ - Distributed job schedulling

https://www.fugue.co/
PAAS on AWS?

http://spinnaker.io/
Spinnaker is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.

http://oneops.com/index.html  - OneOps enables continuous lifecycle management of complex, business-critical application workloads on any cloud-based infrastructure. Made by Walmart

http://fabric8.io/ - Fabric8 is an integrated open source DevOps and Integration Platform which works out of the box on any Kubernetes or OpenShift environment and provides Continuous Delivery, Management, ChatOps and a Chaos Monkey. by RedHat

http://rancher.com/ - A Complete Platform for Running Containers - awsome one!

## Machine learning

https://siftscience.com/
Fight fraud with real time machine learning. Integrate in an afternoon.


## StressTest

https://github.com/emmericp/MoonGen
MoonGen is a fully scriptable high-speed packet generator built on DPDK and LuaJIT. It can saturate a 10 Gbit/s connection with 64 byte packets on a single CPU core while executing user-provided Lua scripts for each packet. Multi-core support allows for even higher rates. It also features precise and accurate timestamping and rate control.

http://www.browserstack.com
Rapidly test your website for cross browser compatibility across 700+ browsers

## Presentations/Blog posts
http://www.slideshare.net/brendangregg/linux-performance-tools
Performance monitoring tools presentation

http://dustinrcollins.com/grabbing-aws-credentials-with-bash

http://malwaretips.com/blogs/malware-removal-guide-for-windows/
Malware removal guide for windows.

http://www.maximumpc.com/article/features/blue_screen_death_survival_guide_every_error_explained
BSOD tutorial

https://www.conetix.com.au/blog/conetix-network-operations-centre-build-part-3
mobnitoring blog entry

https://www.backblaze.com/blog/hard-drive-smart-stats/
smart for drives

http://www.iodigitalsec.com/hard-drive-data-recovery/
dd hdd revovery tutorial

http://blog.codeship.com/virtual-mesos-cluster-vagrant-chef/

http://marceldegraaf.net/2013/06/07/elasticsearch-on-ec2-with-auto-discovery.html
http://marceldegraaf.net/2013/11/05/making-elasticsearch-logstash-and-kibana-play-nice-together.html
ELK stack on AWS

https://medium.com/aws-activate-startup-blog/high-availability-for-mere-mortals-37edab2fd0f9 - how to count availability..

http://steveadams.io/2016/08/03/AMI-to-Docker.html - Ami to docker.

https://medium.com/@eon01/easy-docker-orchestration-with-docker-1-12-aws-efs-and-the-swarm-mode-87d51b6d5ad2 - docker + EFS


## Monitoring/Diagnostic Tools
https://github.com/draios/sysdig/wiki/Sysdig%20Examples
system diagnosis tool

http://sirona.incubator.apache.org/
Apache Sirona aims to provide a simple but extensible monitoring solution for Java applications.

https://www.thousandeyes.com/
BGP, DNS, Network monitoring with nice features.

http://www.panopta.com/
pingdom + pagerduty/victorops in one

http://flapjack.io
monitoring notification routing + event processing system

https://www.twilio.com/
Build the next generation of Voice and SMS applications

http://haydenjames.io/20-top-server-monitoring-application-performance-monitoring-apm-solutions/
monitooring solutions.

http://prometheus.github.io/
An open-source service monitoring system and time series database.

https://bigpanda.io/monitoringscape/
reach monitoring list

https://github.com/Netflix/vector high resolution system and application metrics to every engineer’s browser (like kibana connecting to hosts)

http://www.pcp.io/ Performance Co-Pilot (a.k.a. PCP) is an open source infrastructure for monitoring, visualizing, recording, responding to, and controlling the status, activity, and performance of networks, computers, applications, and servers.

http://www.sysdig.org/ - system-level exploration: capture system state and activity from a running Linux instance, then save, filter and analyze

https://github.com/firehol/netdata - Real-time performance monitoring, done right!

https://github.com/forward3d/uphold - automatic DB backup tests

https://github.com/Yelp/elastalert - alerts based on elasticsarch data

https://www.atatus.com/ - application monitoring (NR alternatives)

https://dripstat.com/ - JVM APM

http://chrononsystems.com/ - Chronon records every change made by every single line of code in your program while it is executing

## Remote Access
http://guac-dev.org/
Guacamole is a clientless remote desktop gateway.

http://synergy-project.org/
its software for sharing one mouse and keyboard between multiple computers on your desk.

https://github.com/yudai/gotty
GoTTY is a simple command line tool that turns your CLI tools into web applications.

http://blog.gravitational.com/gravitational-teleport-1-0-released/
Teleport is modern SSH server designed for clusters of servers and the teams working on them

##  Load Balancers

https://github.com/hipache/hipache
Hipache: a distributed HTTP and websocket proxy

https://github.com/google/seesaw - Google LoadBalancer written in Go based on LVS

https://github.com/twitter/twemproxy - redis/memcache load balancer + zero copy

## Log management
https://github.com/ezotrank/logsend
fast logparser in go

## Dashboards
https://www.virtkick.io/
virtual machines dashboard


## Management

https://taiga.io/
Taiga is a project management platform for startups and agile developers

https://www.phacility.com/ - A complete software development platform (git, tasks, chat, board, etc)

## Helpfull
https://www.checkcentral.cc/
A smarter way to manageyour email notifications

http://www.devopsbookmarks.com/

https://dev-ops-tools.zeef.com/richard.kraayenhagen
devops tools

http://radar.zendesk.com/
High level API and backend for writing web apps that use push messaging

http://searchkick.org/
Searchkick learns what your users are looking for. As more people search, it gets smarter and the results get better. It’s friendly for developers - and magical for your users.

http://www.inspectlet.com/
Record and playback everything visitors do on your site

http://www.layerswp.com/
wordpress site builder

http://vitess.io Vitess is a database solution for scaling MySQL.

https://diff.io/ - difference as a service

http://rocket.chat/ - opensource slack

https://github.com/buger/gor/ - HTTP traffic replay in real-time.

http://stackstorm.com/ - wires together your legos

http://www.pipefy.com/ It helps companies to be always organized

http://raml.org/ - RESTful API Modeling Language (RAML) makes it easy to manage the whole API lifecycle from design to sharing.

http://rickbergfalk.github.io/sqlpad/ - Run SQL in your browser...

http://pouchdb.com/ - PouchDB was created to help web developers build applications that work as well offline as they do online.

https://github.com/tripit/slate - Slate helps you create beautiful API documentation.

https://github.com/Yelp/dumb-init - dumb-init is a simple process supervisor and init system designed to run as PID 1 inside minimal container environments (such as Docker).

## Mobile
https://developers.google.com/cloud-messaging/
Send data from your server to your users' devices, and receive messages from devices on the same connection. The GCM service handles all aspects of queueing of messages and delivery to client applications running on target devices, and it is completely free.


## Security / PCI DSS
http://cloudacademy.com/blog/how-to-make-your-infrastructure-compliant-with-pci-dss-on-aws/

https://vaultproject.io/ A tool for managing secrets.

https://lyft.github.io/confidant/
Confidant solves the authentication chicken and egg problem by using AWS KMS and IAM to allow IAM roles to generate secure authentication tokens that can be verified by Confidant.

https://github.com/coreos/clair
Clair is a container vulnerability analysis service. It provides the list of vulnerabilities that threaten each container and can sends notifications whenever new vulnerabilities that affect existing containers are released.

https://github.com/fugue/credstash
CredStash icredentials mgment and distrib system that uses AWS Key Management Service (KMS) for key wrapping and master-key storage, and DynamoDB for credential storage and sharing.

https://github.com/Netflix/Fido - FIDO’s primary purpose is to handle the heavy manual effort needed to evaluate threats coming from today's security stack and the large number of alerts generated by them


http://resources.infosecinstitute.com/14-popular-web-application-vulnerability-scanners/

https://github.com/toolswatch/vFeed - vFeed Framework is a CVE, CWE and OVAL Compatible naming scheme concept that provides extra structured detailed third-party references and technical characteristics for a CVE entry through an extensible XML/JSON schema

https://keeweb.info/ - Free cross-platform password manager compatible with KeePass

https://www.bro.org/ - Bro is a powerful network analysis framework that is much different from the typical IDS you may know.

https://gist.github.com/maxvt/bb49a6c7243163b8120625fc8ae3f3cd - Irastructure Secret Management Software Overview

https://github.com/gentilkiwi/mimikatz - A little tool to play with Windows security
https://github.com/Netflix/bless - SSH Certificate Authority that runs as a AWS Lambda function

https://github.com/toniblyx/prowler - Tool based on AWS-CLI commands for AWS account hardening


## CI/CD
https://www.go.cd/
https://concourse.ci/ - config in yaml files
https://github.com/lambci/lambci - CI in Lambda


### Tests
http://robotframework.org/ - Robot Framework is a generic test automation framework for acceptance testing and acceptance test-driven development (ATDD).
https://ghostinspector.com/ - Automated UI Testing Made Easy - record via chrome addon
https://github.com/chef/inspec - testing framework for infrastructure
http://serverspec.org/ - With Serverspec, you can write RSpec tests for checking your servers are configured correctly.
https://github.com/k1LoW/awspec - sepecs for AWS
https://github.com/aelsabbahy/goss - Quick and Easy server testing/validation (GO)
https://github.com/philpep/testinfra - Testinfra test your infrastructures (python)


## DPDK stuff
http://www.seastar-project.org/ - Seastar is an advanced, open-source C++ framework for high-performance server applications on modern hardware.
http://www.scylladb.com/ - NoSQL column store database Cassandra compatible based on DPDK

## AWS
https://github.com/PriceBoardIn/aws-elk-billing - AWS biling ok ELK
https://github.com/svolpe43/cfsh - CloudFormation in bash !
https://boxfuse.com/ - Test on VirtualBox, deploy atomically to AWS
https://github.com/awslabs/aws-shell
https://github.com/open-guides/og-aws - AWS open guides/tips/gotchas
https://nccgroup.github.io/Scout2/ - security auditing tool
https://github.com/eawsy/aws-lambda-go-net - execute Go web applications on AWS Lambda and AWS API Gateway
https://github.com/widdix/aws-cf-templates/tree/master/wordpress - wordpress on AWS - using EFS
https://alestic.com/2016/10/aws-git-backed-static-website/ - aws git bakcked static website - lowcost
https://cloudonaut.io/improve-aws-security-protect-your-keys-with-ease/ - multiFA aws credentials
https://stp5.net/blog/post/secrets-in-aws/ - Secrets in AWS
https://www.linkedin.com/groups/6814264/6814264-6228648338527383555 - Cert materials
https://github.com/kubernetes/kops - Launching a Kubernetes cluster hosted on AWS


## Serverless
https://github.com/trek10inc/aws-lambda-debugger - lambda debugger


### CloudFormation
https://github.com/stelligent/cloudformation_templates
http://www.sparkleformation.io/ - multi cloud CloufFormation
https://github.com/cloudtools/troposphere - python library to create AWS CloudFormation
https://github.com/bazaarvoice/cloudformation-ruby-dsl
https://github.com/frontrowed/stratosphere - AWS CloudFormation in Haskell
https://github.com/stevenjack/cfndsl
https://github.com/monken/cfn-include cfn-include is a preprocessor that extends CloudFormation's intrinsic functions.

## DB tools
https://flywaydb.org/ - Evolve your Database Schema easily and reliably across all your instances
liquidbase


## Remote works
https://github.com/lukasz-madon/awesome-remote-job#job-boards - lots of links
https://www.corpinfo.com/careers/ - some guys from reddit
https://weworkremotely.com/categories/6-devops-sysadmin/jobs#intro - remote DevOps work


## Serverless
https://github.com/alestic/lambdash - run shell in lambda
