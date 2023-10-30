---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}



{% include_relative includes/intro.md %}

{% include_relative includes/news.md %}

{% include_relative includes/pub.md %}

{% include_relative includes/edu.md %}

{% include_relative includes/award.md %}

{% include_relative includes/work.md %}

<br />
<br />
<div style="text-align: center; line-height: 100px">
<a href="https://mapmyvisitors.com/web/1bvi9" title="Visit tracker"><img src="https://mapmyvisitors.com/map.png?d=6ifJ0N2S6FVcdRDwfR_wSlW5gbCr0N9-Jxgb3ZqJjPs&cl=ffffff"></a>
</div>
<br />
<br />
