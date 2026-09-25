---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekéri a forma vizuális határait, amelyeket a megjelenített tartalom alapján számít ki.

### Visszatérési érték

A [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait képviseli diavetítési koordinátákban.


```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap az összes, a forma által a megjelenítés során létrehozott tartalom tengelye szerint igazított határait jelöli a diavetítési koordináta térben.

Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlnyúlik a dia kezdőpontján.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó tényezőket, mint például az átalakítások (például forgatás), a vonalvastagság és -csatlakozások, a szövegelrendezés és -túlcsordulás, a SmartArt geometria, valamint egyéb elrendezési hatásokat, amelyek befolyásolják a forma végső megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapjára.


### Lásd még
* osztály [`Table`](/slides/python-net/hu/aspose.slides/table)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)