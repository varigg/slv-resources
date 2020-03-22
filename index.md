---
title: SLV Community Resources
---
This site is a work in progress. Currently it only has a list of [Restaurants](restaurants) that are offering delivery/pickup during the shelter in place. If you have ideas or suggestions for content, please let me know.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>