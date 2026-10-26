---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
A megjelenített tartalom alapján kiszámított alakzat vizuális határait adja vissza.

### Visszatérési érték

A [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef) egy olyan objektum, amely az alakzat vizuális határait jelöli a diák koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a diák koordináta-rendszerben a forma által a renderelés során előállított összes tartalom tengelyhez igazított határait ábrázolja.

Ezek a határok eltérhetnek az alakzat modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik a dia kiindulópontján.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó tényezőket, mint például a transzformációk (például forgatás), a vonalvastagság és illesztések, a szövegelrendezés és túlfutás, a SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják az alakzat végső megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`SmartArtShape`](/slides/python-net/hu/aspose.slides.smartart/smartartshape)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides.smartart`](/slides/python-net/hu/aspose.slides.smartart)
* könyvtár [`Aspose.Slides`](/slides/python-net)