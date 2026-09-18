---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lekéri a forma vizuális határait, amelyek a megjelenített tartalma alapján számítódnak.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely a forma vizuális határait jelöli
             a dia koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap az összes, a forma által a renderelés során előállított tartalom tengely-irányú határait jelöli a dia koordinátaterében.
            
             Ezek a határok eltérhetnek a forma modellhatáraitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom a dia origója utánra nyúlik.
            
             A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, például a transzformációkat (például forgatás), a vonalvastagságot és illeszkedéseket, a szövegelrendezést és túlfutást, a SmartArt geometriát, valamint egyéb elrendezési hatásokat, amelyek befolyásolják a forma végső megjelenését.
            
             A visszaadott határokat a dia téglalapjához nem vágják le.



### Lásd még
* osztály [`SmartArtShape`](/slides/python-net/hu/aspose.slides.smartart/smartartshape)
* modul [`aspose.slides.smartart`](/slides/python-net/hu/aspose.slides.smartart)
* könyvtár [`Aspose.Slides`](/slides/python-net)