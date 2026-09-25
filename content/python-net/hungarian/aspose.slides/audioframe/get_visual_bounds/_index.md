---
title: get_visual_bounds method
second_title: Aspose.Slides Python számára .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
A forma vizuális határait adja vissza, amelyeket a megjelenített tartalmából számoltak ki.

### Visszatér
Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait képviseli a dia koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések
A visszaadott téglalap a forma által a megjelenítés során előállított összes tartalom tengelyigazított határait ábrázolja a dia koordináta térben.

Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)) és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlnyúlik a dia origón.

A vizuális határok figyelembe veszik a megjelenítéssel kapcsolatos szempontokat, mint például a transzformációk (például forgatás), a vonalvastagság és illeszkedések, a szöveg elrendezése és túlcsordulása, a SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végső megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`AudioFrame`](/slides/python-net/hu/aspose.slides/audioframe)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)