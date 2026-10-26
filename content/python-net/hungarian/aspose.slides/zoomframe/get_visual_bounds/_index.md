---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A forma megjelenített tartalma alapján kiszámított vizuális határait adja vissza.

### Visszatérési érték

[`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait ábrázolja dia koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a forma által a renderelés során előállított összes tartalom tengelyre igazított határait ábrázolja a dia koordináta térben.

Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlteszi a dia kiindulópontját.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó tényezőket, mint például a transzformációk (például forgatás), a vonalvastagságok és illesztések, a szövegelrendezés és túlfutás, a SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végleges megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`ZoomFrame`](/slides/python-net/hu/aspose.slides/zoomframe)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)