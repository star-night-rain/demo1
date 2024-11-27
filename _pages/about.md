---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

### National awards

{% for award in site.data.awards.national-awards %}

- {{award.competition}},<span style="color:#f4b757">{{award.rank}}</span>,{{award.date}}

{% endfor %}

### Provincial awards

{% for award in site.data.awards.provincial-awards %}

- {{award.competition}},<span style="color:#845EC2">{{award.rank}}</span>,{{award.date}}

{% endfor %}

### University awards

{% for award in site.data.awards.university-awards %}

- {{award.competition}},<span style="color:#3e91f2">{{award.rank}}</span>,{{award.date}}

{% endfor %}
