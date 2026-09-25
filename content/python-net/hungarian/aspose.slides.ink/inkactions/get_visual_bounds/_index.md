---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A forma vizuális határait adja vissza, amely a renderelt tartalom alapján számítódik.

### Returns

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait jelöli
             diavetítési koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap az összes tartalom tengelyre igazított határait jelenti
             amelyet az alakzat a renderelés során hoz létre a diavetítési koordináta térben.

             Ezek a határok eltérhetnek az alakzat modellhatáraitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik
             a dia eredetén.

             A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, például
             a transzformációkat (például a forgást), a vonalvastagságot és csatlakozásokat,
             a szövegelrendezést és az átfedést, a SmartArt geometriát, valamint egyéb elrendezési hatásokat,
             amelyek befolyásolják az alakzat végső megjelenését.

             A visszaadott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`InkActions`](/slides/python-net/hu/aspose.slides.ink/inkactions)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides.ink`](/slides/python-net/hu/aspose.slides.ink)
* könyvtár [`Aspose.Slides`](/slides/python-net)