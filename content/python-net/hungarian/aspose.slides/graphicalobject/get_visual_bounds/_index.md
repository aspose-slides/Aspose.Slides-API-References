---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A forma megjelenített tartalmából számított vizuális határolókat adja vissza.

### Visszatérési érték

A [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef) ami a forma vizuális határolóit ábrázolja
             diavetítés koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a forma által a megjelenítés során előállított összes tartalom tengely-igazított határolóit ábrázolja a diavetítés koordinátarendszerében.
             
             Ezek a határolók eltérhetnek a forma modellhatárolóitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlnyúlik a dia kiindulópontján.
             
             A vizuális határolók figyelembe veszik a megjelenítéssel kapcsolatos tényezőket, mint például az átalakítások (például forgatás), vonalvastagság és illesztések,
             szövegelrendezés és túlcsordulás, SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végső megjelenését.
             
             A visszaadott határolók nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)