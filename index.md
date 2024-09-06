---
layout: page
title: Schedule
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
Peking University, 2024 Fall
{: .mb-0 .fs-6 .text-grey-dk-000 }

<p>
<a href="https://autolab.pku.edu.cn" class="btn btn-purple">Autolab</a>
<a href="https://course.pku.edu.cn" class="btn btn-green">PKU Course Website</a>
</p>

## Schedule
{% for module in site.modules %}
<a name="week-{{module.weekNumber}}"></a>
{{ module }}
{% endfor %}