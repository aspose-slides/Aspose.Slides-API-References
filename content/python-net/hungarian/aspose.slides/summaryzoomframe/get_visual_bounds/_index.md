---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekéri a forma vizuális határait, amelyeket a megjelenített tartalma alapján számol.

### Visszatérési érték

A **aspose.slides.RectangleF** amely a forma vizuális határait jelöli
             a dia koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap az összes tartalom tengelyhez igazított határait ábrázolja,
 amelyet a forma a megjelenítés során a dia koordinátarendszerében előállít.

Ezek a határok eltérhetnek a forma modellhatáraitól
 ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
 [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
 és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom a dia kiindulási pontja
 felett túlnyúlik.

A vizuális határok figyelembe veszik a megjelenítéshez kapcsolódó tényezőket, például
 transzformációkat (például forgatás), vonalvastagságot és illesztéseket,
 a szöveg elrendezését és túlcsordulását, a SmartArt geometriáját, valamint egyéb elrendezési hatásokat,
 amelyek befolyásolják a forma végső megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`SummaryZoomFrame`](/slides/python-net/hu/aspose.slides/summaryzoomframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)