---
title: set_metered_key method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Ställer in mättad offentlig och privat nyckel.
Om du köper en mättad licens, bör detta API anropas när applikationen startas; normalt är det tillräckligt. 
Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, sätts licensen till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensens status; om den är i utvärderingsstatus, anropa detta API igen.

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| public_key | **str** | offentlig nyckel |
| private_key | **str** | privat nyckel |

### Se också
* klass [`Metered`](/slides/python-net/sv/aspose.slides/metered)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)