---
title: get_visual_bounds method
second_title: Aspose.Slides Python számára a .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
A forma vizuális határait adja vissza, melyek a megjelenített tartalom alapján számítódnak.

### Visszatérési érték

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait jelöli a diára vonatkozó koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a diára vonatkozó koordináta térben a forma által a renderelés során előállított összes tartalom tengely-igazított határait jelöli.

Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlnyúlik a dia origóján.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó tényezőket, mint például a transzformációk (például forgatás), a vonalszélesség és illesztések, a szöveg elrendezése és túlcsordulása, a SmartArt geometria, valamint más elrendezési hatások, amelyek a forma végső megjelenését befolyásolják.

A visszaadott határokat nem vágják le a dia téglalapjára.



### Lásd még
* osztály [`PictureFrame`](/slides/python-net/hu/aspose.slides/pictureframe)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)