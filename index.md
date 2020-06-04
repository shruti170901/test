---
layout: default
---

{% include 01-name.md %}

<br>

{% include 02-image.md %}

<br>

{% include 03-links.md %}

<br>

{% include 04-lists.md %}

<br>

{% include 05-emphasis.md %}


{% if page.tipue_search_active or layout.tipue_search_active %}
<link rel="stylesheet" href="{{ "/assets/tipuesearch/css/normalize.css" | relative_url }}">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="{{ "/assets/tipuesearch/tipuesearch_content.js" | relative_url }}"></script>
<link rel="stylesheet" href="{{ "/assets/tipuesearch/css/tipuesearch.css" | relative_url }}">
<script src="{{ "/assets/tipuesearch/tipuesearch_set.js" | relative_url }}"></script>
<script src="{{ "/assets/tipuesearch/tipuesearch.min.js" | relative_url }}"></script>
{% endif %}
