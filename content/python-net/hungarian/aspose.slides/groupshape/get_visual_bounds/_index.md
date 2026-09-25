---
title: get_visual_bounds method
second_title: Aspose.Slides a .NET-en keresztül Python API referencia
description: 
type: docs
url: /hu/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekéri az alakzat vizuális határait, amelyeket a megjelenített tartalma alapján számol.

### Visszatérési érték

A [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef) amely az alakzat vizuális határait ábrázolja diavetítés koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap az összes tartalom tengelyre igazított határait ábrázolja, amelyet az alakzat a megjelenítés során a diavetítés koordináta térben hoz létre.
            
            Ezek a határok eltérhetnek az alakzat modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlnyúlik a diavetítés kiindulópontján.
            
            A vizuális határok figyelembe veszik a rendereléshez kapcsolódó tényezőket, például a transzformációkat (például forgatás), a vonalvastagságot és illesztéseket, a szöveg elrendezését és túlcsordulását, a SmartArt geometriáját, valamint egyéb elrendezési hatásokat, amelyek befolyásolják az alakzat végső megjelenését.
            
            A visszaadott határok nincsenek levágva a diavetítés téglalapjára.



### Lásd még
* osztály [`GroupShape`](/slides/python-net/hu/aspose.slides/groupshape)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)