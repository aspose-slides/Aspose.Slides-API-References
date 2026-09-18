---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Visszaadja az alakzat megjelenített tartalma alapján kiszámított vizuális határolókat.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely az alakzat vizuális határolóit jelöli diavetítés koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a tengely-igazított határolókat tartalmazza minden, az alakzat által a megjelenítés során a diavetítés koordináta-rendszerében előállított tartalomra.

Ezek a határolók eltérhetnek az alakzat modellhatárolóitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom a dia origóját meghaladja.

A vizuális határolók figyelembe veszik a megjelenítéssel kapcsolatos tényezőket, mint a transzformációk (például forgatás), vonalvastagság és illesztések, szövegelrendezés és túlcsordulás, SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják az alakzat végső megjelenését.

A visszaadott határolókat nem vágják le a dia téglalapjára.



### Lásd még
* osztály [`AutoShape`](/slides/python-net/hu/aspose.slides/autoshape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)