---
layout: default
title: Cobbler - Linux install and update server
---
# Welcome to Cobbler
Cobbler is a Linux installation server that allows for rapid setup of network installation environments. It glues together and automates many associated Linux tasks so you do not have to hop between lots of various commands and applications when rolling out new systems, and, in some cases, changing existing ones.  It can help with installation, DNS, DHCP, package updates, power management, configuration management orchestration, and much more.

{% for post in site.posts limit:5 %}
## [{{ post.title}}]({{post.url}})
<p class="postauthor"><i>Posted by {{ post.author }} on {{ post.date | date: "%A, %B %d, %Y" }}</i></p>
{{post.content}}
{% endfor %}
