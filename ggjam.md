---
layout: page
title: "GG Jam"
permalink: /ggjam
---

**GG Jam** is our annual video game hackathon. Teams of upto 4 spend 24 hours creating a unique game, based on a theme that we give on the day of the event.

***

{% for post in site.categories.ggjam %}

## [{{post.title}}]({{post.permalink}})

{{post.content}}
    
{% endfor %}

