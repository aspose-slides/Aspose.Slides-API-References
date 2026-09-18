---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás alapján
description: 
type: docs
url: /hu/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
A forma vizuális határait adja vissza, amelyek a megjelenített tartalma alapján számítódnak.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely a forma vizuális határait képviseli
             diaképkordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap az összes tartalom tengely irányú határait ábrázolja
             amelyet a forma a diaképkordináta térben történő renderelés során hoz létre.
            
             Ezek a határok eltérhetnek a forma modellhatáraitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat tartalmazhatnak, ha a renderelt tartalom túlnyúlik
             a diák eredetén túl.
            
             A vizuális határok figyelembe veszik a rendereléshez kapcsolódó aspektusokat, például
             transzformációkat (például forgatás), vonalvastagságot és illesztéseket,
             szöveg elrendezést és túlcsordulást, SmartArt geometriát, és további elrendezési hatásokat
             amelyek befolyásolják a forma végső renderelt megjelenését.
            
             A visszaadott határok nincsenek levágva a diák téglalapra.



### Lásd még
* class [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)