#Coastguard.io

##Premise
An insanely beautiful visualization and infographic utility that turns your everyday docker-lovin’ sysadmin into a goddamn wizard of infinite power and knowledge.  New containers and hosts materialize out of thin (html-powered) air right before your very eyes.  Crazy helpful pixels of infographic magic caress your retina-cells with streams of all-knowing information.  You get the idea.  The ultimate docker visualization platform that works no matter where you run docker.

## The problem
Docker-powered deployments do not inherently provide a visual way to answer the following questions:

* How/where are your containers currently distributed?
* How many of a given type of container are currently running? 
* What is your biggest container workload?
* Are there wasteful or unnecessary workloads occurring?
 

## The pitch

From 0 to Docker-compatible (native) dashboard in no time. 

No more, “You run our tool to run your containers and we will show you how they look on our platform”.  Instant docker monitoring and visualization.  

## 

## MVP coastguard.io

Metrics sorted high importance to lowest

###High importance (at a glance metrics):

**Host level**:  

* CPU (overall usage of host)
* memory usage (overall consumption vs available limit)

**Container level**: 

* memory (individual container memory consumption)
* CPU consumption (individual container CPU usage)
 
###Medium importance (available via drilldown..?):

**Host level**: 

* Network ingress / egress (simple totals would be fine)
* Uptime

###Low importance

**Host level**: Docker Image counts 

**Key metrics/events**:
Metrics
Container: Docker documentation
CPU 
Memory (usage vs limit)
I/O
Network (tx/rx)
Running time
Links (what containers are linked together)

Host:
CPU
OS
Total Memory
Total images
Container state
running
stopped
Docker information
docker version
Events
Container
Create
Destroy
Die
Pause
Start
Restart
Stop

## UI/UX

### Early prototype


![test](http://iamnayr.com/content/images/2015/07/coastguard-1.png)
