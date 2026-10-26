---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET API-referencián keresztül
description: 
type: docs
url: /hu/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A forma vizuális határait számítja ki a renderelt tartalma alapján.

### Visszatérési érték

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait jelöli a
             diák koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a forma által a renderelés során előállított összes tartalom tengelyen igazított határait jelöli a diák koordinátra térben.

Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)) és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik a diák kiindulási pontján.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, például a transzformációkat (például forgatás), a vonalvastagságot és illeszkedéseket, a szöveg elrendezését és túlfutását, a SmartArt geometriát, valamint más elrendezési hatásokat, amelyek befolyásolják a forma végső megjelenését.

A visszaadott határokat nem vágja le a diák téglalapja.



### Lásd még
* osztály [`SmartArt`](/slides/python-net/hu/aspose.slides.smartart/smartart)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides.smartart`](/slides/python-net/hu/aspose.slides.smartart)
* könyvtár [`Aspose.Slides`](/slides/python-net)