##Tim Fall

####Introduction
<iframe src="http://githubbadge.appspot.com/timfallmk?s=1" style="border: 0;height: 142px;width: 200px;overflow: hidden;" frameBorder="0"></iframe>

----

###Experience
####**Chief Solutions Architect**
#####Mesosphere _2015-2015_
Second Solutions Architect hired for Mesosphere. Helped run the Solutions Architect team, and informed the hiring and training process for new members. Also helped build out solutions based on the DCOS (**D**ata**C**enter **O**perating **S**ystem) product from Mesosphere.

Responsible for covering all aspects of Mesosphere DCOS and Mesos deployment. This included, installation buildout and creation, deployment in customer environments, customization for customer use cases and variables, code changes and contributions based on customer feedback, deep dives and end-to-end knowledge of technology involved, professional services, etc.

Also responsible for evangelism of Mesosphere products, including hosting meetups and convention speeches, product overviews and discussions with developers and community, managing feedback and ecosystem componenets, as well as general and in depth knowledge sharing about Mesos and Mesosphere DCOS.

Although responsibilities could range over the full spectrum of tasks, from dev to sales, major time was also spent on core development for parts of the ecosystem. Feedback from the field, as well as improvements and fixes that needed to be made were considered part of this reponsibility.
####**Chief Cloud and Network Architect**
#####Midokura  _2013 - 2015_
Chief Cloud and Network Architect for Midokura. Created and trained system engineering team as well as oversaw product integration. Member of Professional Services team and evangelism/technical preview participation.

Core focus on developing product integration, professional services and consulting, as well as evangelism and technical presentations. Developed several key projects (see [below](#skills) for details and examples) for integrating and deploying [MidoNet][11] into other systems. Oversaw open source community integration effort. Integration into a number of projects is currently under active development.

Lead and created [containerization][8] effort. Created spec for containerizing [MidoNet][11] in an OpenStack-based cloud environments, as well as developing first-class-citizen SDN for Docker (and other container solutions). Fully containerized all [MidoNet][11] components, and designed distributed deployment and running version to be used on modern distributed systems. Project will form the basis for native Docker networking in co-development with `libnetwork` (see [bees](#bees)).

Other major responsibilites included core-development and debugging, customer-facing QA and support, and development of tech-talks designed to familiarize the community with SDN and the ecosystem. These contributions required intimate familiarity with the technology and state of development for componenets like containers, Linux kernel development (networking componenets specifically), cloud orchestration, SDN developments, networking developments, etc.

####**VP of IT and Infrastructure**
#####Airtime Media Inc.  _2012 - 2013_
Founding member of the operations/IT team for Airtime.com. Responsible for design and maintenance of internal systems and data platforms. Also established and implemented inventory tracking, remote operations, and scalability projects. Primary specialty in creating operations structures for companies just now needing them.

####**Owner/Founder**
#####SG-1 Technologies  _2004 - 2013_
Founder and owner of data consulting firm specializing in deployment of computing systems and electronics as well as networks for small businesses. To date, SG-1 Technology Enterprises has seven active clients.

Coordinated, designed, and managed all campus computer and networking systems for Menlo School in Atherton, CA. Expertise in Unix, Windows, and Mac architecture, including set up of wireless networks, centralized student account storage, universal portal access, and interactive student displays.

Consultant to Menlo School in design of new campus “smart” classrooms and facilities. These classrooms incorporated multiple presentation systems to expand educational involvement. Redesigned network layout and developed new security measures allowing greater access and stricter monitoring.

Networking and website design for Roberts and Company Inc. Design of offsite networking conditions as well as front page and presentation management.

Seven years experience in theatrical lighting design for plays and some cinema. This includes design and maintenance of high power electrical and control systems.

Design and implementation of home interconnectivity project for client of SG-1 Technologies. Provides for centralized, easy, electronic control of all home systems (entertainment, security, phone, etc.)

#####*Biological Experience*
*For information on biological experience and skills please see the [`tl;dr`][tl;dr] version*

-------
###Education
* Menlo School, graduation 06/2005
	* G.P.A. 3.6
	* Six Advanced Placement courses, two honors courses
	* Technological Development Award and Scientific Advancement Award
	* National Merit Finalist
* UCSC 2005-2007
* Trinity College 2007-2009
	* Faculty Honors
	* Major: B.S. Neuroscience
	* GPA: 3.75

---
###Skills {#that-pay-said-bills}
####Technology
Primary recent work involving cloud based systems including orchestration, storage, components, and development. Heavy work in software-based networking design (SDN) for cloud and other environments. Deeply involved in cloud development communities, including [OpenStack][1], [Mesosphere][2], [Docker][3], [CoreOS][5], and related technologies (Docker Swarm, `etcd`, `kubernetes`, `libvirt`, `rkt`, Docker Machine, *and many others I've forogtten*)
**Contributions to most projects done upstream**

*Previous work included*:
Extensive knowledge of computer systems and networking equipment as well as programming experience in Java, Basic, and C Languages. Proficient in Adobe and Microsoft Programs. Proficient in Java, Javascript, C, C++, Objective C, SQL, Apache, TCP/IP, database management, VOIP, HTML, XML, and Unix and Linux administration and use. Web and interface design experience. Capable of using any operating system. Experienced in design and repair of hardware and software.

Expertise in design and management of centralized, user-based networks. Knowledge of network design and components. Primary experience with setup of user friendly networks.

####Biological
*For information on biological experience and skills please see the [`tl;dr`][tl;dr] version*

------
###Projects, Code Highights, and other Fun Stuff
Here's a (from from comprehensive) list of my recent projects, ones I've contributed to, and other things I like to play with:
#####Bees
*[`bees`](https://github.com/midonet/bees) is project to bring true open source and full featured SDN to containers and other distributed systems. It is designed to make all componenets distributed and leverages [MidoNet][11] for the backend.*

>**Note**: This is part of a soon-to-be announced project in joint development with Docker [`libnetwork`](https://blog.docker.com/2015/04/docker-networking-takes-a-step-in-the-right-direction-2/)


>MidoNet for Docker Swarm, CoreOS Kubernetes, Konsole, and other cluster management tools
>
>[![Docker build](http://dockeri.co/image/timfallmk/bees)](https://registry.hub.docker.com/u/timfallmk/bees)

#####Arrakis
*[Arrakis](https://github.com/midonet/arrakis) is a collection of Puppet modules to deploy and configure [MidoNet][11] as an option for networking in OpenStack. It is aligned with (and developed against) the upstream Puppet modules for deploying OpenStack on [StackForge][9]. It's development also contributed code for making these default modules into a plugin framework capable of accepting multiple [providers][10].*

#####Current Work
*Currently I am working on, and contributing to these projects. But who knows, this could change from minute to minute!*

* Docker Swarm
* CoreOS
	* `fleet` orchestration
	* `etcd` development and features
	* Networking
* Kubernetes
	* SDN
	* Plugin in frameworks for networking
* Docker Machine


[1]:https://www.openstack.org/
[2]:https://mesosphere.com/
[3]:https://www.docker.com/
[4]:https://hub.docker.com/u/timfallmk/
[5]:https://coreos.com/
[6]:https://coreos.com/etcd/
[7]:http://kubernetes.io/
[tl;dr]:http://gist.github.io/something
[8]:https://github.com/midonet/bees
[9]:https://github.com/stackforge
[10]:https://github.com/stackforge/networking-midonet
[11]:http://midonet.org/
