---
title: "{{ replace .Name "-" " " | title }}"
keywords: ["Manastirea Calui"]
date: {{ .Date }}
draft: true
type: other
layout:
sitemap_exclude: false

sitemap:
  changefreq: weekly
  filename: sitemap.xml
  priority: 1

---