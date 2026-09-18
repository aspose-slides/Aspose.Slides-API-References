---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
A forma megjelenített tartalma alapján kiszámított vizuális határokat adja vissza.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely a forma vizuális határait
             slide koordinátákban reprezentálja.


```python
def get_visual_bounds(self):
    ...
```

### Megjegyzés

A visszaadott téglalap a forma által a renderelés során előállított összes tartalom
             tengelyre igazított határait képviseli a slide koordináta térben.

Ezek a határok eltérhetnek a forma modell határaitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és tartalmazhatnak negatív koordinátákat, ha a renderelt tartalom túllépi a slide kiindulópontját.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, például
             a transzformációkat (például forgatás), vonalvastagságot és illesztéseket,
             szöveg elrendezést és túlcsordulást, a SmartArt geometriát, valamint egyéb
             elrendezési hatásokat, amelyek befolyásolják a forma végső megjelenését.

A visszaadott határokat nem vágják le a slide téglalapra.

### Lásd még
* osztály [`PictureFrame`](/slides/python-net/hu/aspose.slides/pictureframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)