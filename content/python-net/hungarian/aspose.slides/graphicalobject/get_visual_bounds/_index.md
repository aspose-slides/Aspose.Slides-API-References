---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A forma megjelenített tartalma alapján kiszámított vizuális határait adja vissza.

### Visszatérési érték

Egy **aspose.slides.RectangleF** objektum, amely a forma vizuális határait jelöli a diák koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap az összes, a forma által a renderelés során előállított tartalom tengelyre igazított határait ábrázolja a diák koordináta-rendszerében.

Ezek a határok eltérhetnek a forma modell határaitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom a dia origóján túlra nyúlik.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, például a transzformációkat (például forgatás), a vonalvastagságot és illeszkedéseket, a szöveg elrendezését és túlcsordulását, a SmartArt geometriát, valamint egyéb elrendezési hatásokat, amelyek befolyásolják a forma végleges megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapra.



### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)