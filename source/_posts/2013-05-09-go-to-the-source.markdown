---
layout: post
title: "Read The Source"
date: 2013-05-09 19:46
comments: true
categories: 
---
{% img http://i.imgur.com/TA1kG9A.jpg %}
I've come to realize the marked difference that separates a good software engineer from a great engineer out of school, is their apititude and attitude towards reading source code. This applies whether you are a front end facing client developer or one working on large backend systems.

Over the course of the last year I've transitioned from Android application development to automated deployment and backend systems. Before, we had a 1 man operations team that couldn't keep up with constant deployments, so a group of 3 engineers were brought together to setup multiple server environments and automate the code deployment process. We chose to use the opensource framework, Chef. Much to my chagrin, their documentation is either terrible or out of date. Luckily Chef is opensouce and all their code can be found on [GitHub](https://github.com/opscode/chef?source=c). This has been a lifesaver. Reading the source code along side their documentation helps vastly in understanding Chef's custom DSL language. There are also a lot of places where the documentation fails to cover proper command line arguments or configuration settings. Chef isn't alone in this failure. Before this I've found that Android's developer pages also a field of uncertainty. Most open source or internal projects are just like this; best documentation practice often forgone for sprint features.

Next time you're uncertain about some program's behavior, don't be so quick to ask, use the source. You'll come away with a deeper understanding of the code you interact with on a day to day basis. It'll allow you to patch, write plugins, and be more certain of upstream updates.

