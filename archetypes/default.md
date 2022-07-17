---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
archives : ["{{ dateFormat "2006/01" .Date }}"]


---
