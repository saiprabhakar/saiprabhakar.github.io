---
layout: page
permalink: /publications/
title: publications
description: For up to date list see my Google Scholar page.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<p style="margin-bottom: 1.5rem;">
  For up to date list see my <a href="https://scholar.google.com/citations?hl=en&user=avFhCGUAAAAJ" target="_blank">Google Scholar page</a>.
</p>

<div class="publications">

{% bibliography %}

</div>

<!-- Social -->
<div class="social">
  <div class="contact-icons">{% include social.liquid %}</div>
  <div class="contact-note">{{ site.contact_note }}</div>
</div>
