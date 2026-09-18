---
title: get_visual_bounds method
second_title: Aspose.Slides a Python .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekéri a forma vizuális határait, amelyeket a megjelenített tartalom alapján számol.

### Visszatérési érték
A **aspose.slides.RectangleF**, amely a forma vizuális határait képviseli dia koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések
A visszaadott téglalap az összes, a forma által a renderelés során előállított tartalom tengely-igazított határait ábrázolja dia koordináta-terben.

Ezek a határok eltérhetnek a forma modell határaitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik a dia origón.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, például az átalakításokat (például forgatás), vonalvastagságot és illesztéseket, szövegelrendezést és túlcsordulást, a SmartArt geometriát, valamint egyéb elrendezési hatásokat, amelyek befolyásolják a forma végső megjelenését.

A visszaadott határokat nem vágják le a dia téglalaphoz.



### Lásd még
* osztály [`ZoomObject`](/slides/python-net/hu/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)