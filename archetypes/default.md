---
date: "{{ .Date }}"
draft: true
tags:
- red
- green
- blue
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
---