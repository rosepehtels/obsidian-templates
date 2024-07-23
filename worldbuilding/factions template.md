---
tags:
  - eldoria/faction
Characters: 
Description: 
Name: "{{title}}"
Items: 
Leader: 
LocatedIn:
---
# Members
```dataview
TABLE location as "Location", status as "Status"
WHERE (econtains(tags, "npc") and (econtains(faction, this.name) or econtains(faction, link(this.name)))) and !econtains(tags, "template")
SORT name asc
```

# Notes
* 
