---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekéri az alakzat vizuális határait, amelyeket a megjelenített tartalma alapján számoltak ki.

### Visszatérési érték

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef) amely a vizuális határokat jelöli
             dia koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzés

A visszaadott téglalap az alakzat által a renderelés során előállított összes tartalom tengelyhez igazított határait jelöli a dia koordináta térben.

             Ezek a határok eltérhetnek az alakzat modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik a dia origón.

             A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például a transzformációk (például forgatás), a vonalvastagság és illeszkedések, a szöveg elrendezése és túlcsordulása, a SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják az alakzat végső megjelenését.

             A visszaadott határokat nem vágják le a dia téglalapra.



### Lásd még
* osztály [`SectionZoomFrame`](/slides/python-net/hu/aspose.slides/sectionzoomframe)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)