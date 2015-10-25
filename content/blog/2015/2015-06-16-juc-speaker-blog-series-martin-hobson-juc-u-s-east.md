---
:layout: post
:title: 'JUC Speaker Blog Series: Martin Hobson, JUC U.S. East'
:nodeid: 568
:created: 1434493177
:tags:
- general
:author: hinman
---
<div style="float:right; margin:1em">
<img src="https://jenkins-ci.org/sites/default/files/images/Jenkins_Butler_0.png" width=114 height=128>
</div>

<p>I’ve been using Jenkins for some time now as the build server for the various projects that are assigned to our four-person software development team, but recently I had exposure to how things were done in a much larger team, and I came away with a better understanding of the kinds of demands that are placed on a build pipeline in these environments. It was quite an education – while the CI pipelines that I administer in our small team might require a handful of virtual machines in our corporate cloud, the pipeline in this team supported over one hundred developers and required several hundred VM instances at any given time.</p>

<p>When operating at this scale, efficiency does become important, as the Amazon cloud charges add up and become significant at this level. Using some relatively simple techniques, I was able to gain insight into what actually happened in the more complex build jobs and learned just how these VM instances were utilized. These build jobs configured over a dozen virtual machines each, and understanding the startup and execution flows was critical to making changes and improving efficiencies. I will be discussing how to instrument and analyze these complex builds in my Lightning Talk: <a href="http://www.cloudbees.com/jenkins/juc-2015/abstracts/us-east/01-02-1615-hobson">"Visualizing VM Provisioning with Jenkins and Google Charts”</a> and hope to see you all there!</p>

<div style="float:left; margin:1em">
<img src="http://jenkins-ci.org/sites/default/files/images/01-02-1615-hobson_0.jpg" width=152 height=182>
</div>

<p>This post is by Martin Hobson, Senior Software Developer at Agilex Technologies. If you have your ticket to <a href="http://www.cloudbees.com/jenkins/juc-2015/us-east">JUC U.S. East</a>, you can attend his lightning talk <a href="http://www.cloudbees.com/jenkins/juc-2015/abstracts/us-east/01-02-1615-hobson">"Visualizing VM Provisioning with Jenkins and Google Charts"</a> on Day 1.</p>

<p><i>JUC IS HERE! JUC U.S. East will begin with registration at 7AM, Thursday June 18. The two day conference is sure to be a blast! If you have not registered, you can still get a ticket! <a href="http://www.cloudbees.com/jenkins/juc-2015/us-east">Check out the agenda for JUC U.S. East here and find the link to register.</a></i></p>
<br><br>
<p><b>Thank you to our <a href="http://www.cloudbees.com/jenkins/juc-2015/sponsors">sponsors</a> for the 2015 Jenkins User Conference World Tour:</p></b>

<div style="float:left; margin:0em">
<img src="http://jenkins-ci.org/sites/default/files/images/sponsors-06032015-02_0.png" width=598 height=579>
</div>