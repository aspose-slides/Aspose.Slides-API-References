---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
A forma vizuális határait adja vissza, amely a renderelt tartalmából számított.

### Visszatérési érték

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait képzi a dián koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzés

A visszaadott téglalap az összes tartalom tengelymenti határait jelöli, amelyet a forma a renderelés során a diák koordináta térben hoz létre.

Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik a dia eredetén.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például a transzformációk (például forgatás), a körvonal szélessége és illesztései, a szöveg elrendezése és túlcsordulása, a SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végső megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`Chart`](/slides/python-net/hu/aspose.slides.charts/chart)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)