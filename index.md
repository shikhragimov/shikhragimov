---
layout: default
title: shikhragimov
---

# AI Researcher & Machine Learning Engineer

10+ years of experience in data science, machine learning, and building production ML systems across Healthcare, FinTech, Oil & Gas, and other industries.

At RiverLab, I combine scientific research, applied machine learning, and systems engineering, with a focus on neural architectures, graph-based modeling, knowledge representation, LLM systems, and open-source development.

<div class="posts">
{% for item in site.pages %}{% if item.layout == "post" %}
<p><a href="{{ item.url | relative_url }}">{{ item.title }}</a>{% if item.date %} <time datetime="{{ item.date | date: '%Y-%m-%d' }}">{{ item.date | date: "%B %-d, %Y" }}</time>{% endif %}</p>
{% endif %}{% endfor %}
</div>
