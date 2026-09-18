---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A forma megjelenített tartalma alapján kiszámított vizuális határokat adja vissza.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely a forma vizuális határait képzi a dia koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a forma által a megjelenítés során előállított összes tartalom tengelyre igazított határait jelöli a dia koordináta térben.

Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlnyúlik a dia eredetén.

A vizuális határok figyelembe veszik a megjelenítéshez kapcsolódó szempontokat, például a transzformációkat (például forgás), a vonalvastagságot és illeszkedéseket, a szövegelrendezést és túlcsordulást, a SmartArt geometriát, valamint egyéb elrendezési effektusokat, amelyek befolyásolják a forma végső megjelenését.

A visszaadott határokat nem vágják le a dia téglalapjára.



### Lásd még
* osztály [`OleObjectFrame`](/slides/python-net/hu/aspose.slides/oleobjectframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)