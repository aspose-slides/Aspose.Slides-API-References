---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A forma megjelenített tartalma alapján kiszámított vizuális határokat adja vissza.

### Visszatérési érték

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait képviseli diavetítés koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a forma által a megjelenítés során előállított összes tartalom tengelyekhez igazított határait jelöli a diavetítés koordináta térben.

Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlnyúlik a dia eredetén.

A vizuális határok figyelembe veszik a megjelenítéssel kapcsolatos szempontokat, mint például az átalakítások (például forgatás), a vonalvastagság és egyesítések, a szöveg elrendezése és túlcsordulása, a SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végső megjelenését.

A visszaadott határokat nem vágják le a dia téglalapra.



### Lásd még
* osztály [`OleObjectFrame`](/slides/python-net/hu/aspose.slides/oleobjectframe)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)