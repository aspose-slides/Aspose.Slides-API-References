---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A renderelt tartalom alapján számított alakzat vizuális határait adja vissza.

### Returns

A [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef) amely az alakzat vizuális határait jelzi
             dia koordinátákban.

```python
def get_visual_bounds(self):
    ...
```

### Remarks

A visszaadott téglalap az összes tartalom tengelyigazított határait jelöli
             amelyet az alakzat a renderelés során a dia koordináta térben hoz létre.

Ezek a határok eltérhetnek az alakzat modellhatáraitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat tartalmazhatnak, ha a renderelt tartalom kiterjed
             a dia origója túlra.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például
             transzformációk (például forgatás), körvonalvastagság és illesztések,
             szöveg elrendezés és túlcsordulás, SmartArt geometria, és egyéb elrendezési hatások,
             amelyek befolyásolják az alakzat végső megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapra.

### Lásd még

* osztály [`Ink`](/slides/python-net/hu/aspose.slides.ink/ink)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides.ink`](/slides/python-net/hu/aspose.slides.ink)
* könyvtár [`Aspose.Slides`](/slides/python-net)