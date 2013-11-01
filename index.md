---
layout: default
title: NaNoWriMo 2013
---

# NaNoWriMo 2013

This is Neil Martinsen-Burrell's novel project for NaNoWriMo 2013
<nanowrimo.org>

This content is licensed under the
<http://creativecommons.org/licenses/by-nc-sa/3.0/us/> Creative Commons
Attribution-NonCommercial-ShareAlike (CC-BY-NC-SA) license.  It is open source
and may be adapted for use by others, but those adaptations may not be used
commercially, and they also must be made available under these same license
terms.

{% for post in site.posts reversed %}
+ {{ post.date | date_to_string }} -> [{{ post.title }}]({{ post.url }})
{% endfor %}