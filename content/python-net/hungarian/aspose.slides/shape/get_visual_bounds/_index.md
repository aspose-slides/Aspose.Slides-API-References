---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekéri a shape vizuális határait, amelyeket a megjelenített tartalma alapján számol.

### Visszatérési érték

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely az alakzat vizuális határait reprezentálja
             a diák koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a tengely-igazított határait ábrázolja az összes tartalomnak
             amelyet az alakzat a megjelenítés során a diák koordináta-rendszerben előállít.

             
             Ezek a határok eltérhetnek az alakzat modellhatáraitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túllépi a dia origóját.
             
             A vizuális határok figyelembe veszik a rendereléshez kapcsolódó tényezőket, például
             a transzformációkat (például forgatás), a vonalvastagságot és csatlakozásokat,
             a szövegelrendezést és túlcsordulást, a SmartArt geometriát, valamint egyéb elrendezési hatásokat,
             amelyek befolyásolják az alakzat végső megjelenését.
             
             A visszaadott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)