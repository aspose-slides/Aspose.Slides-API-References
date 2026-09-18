---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
A forma megjelenített tartalmából számított vizuális határokat adja vissza.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely a forma vizuális határait ábrázolja
             diavetítés koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzés

A visszaadott téglalap az összes tartalom tengely-alapú határait jelöli,
             amelyet a forma a renderelés során hoz létre a diavetítés koordináta-terében.
             
             Ezek a határok eltérhetnek a forma modellhatáraitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat tartalmazhatnak, ha a renderelt tartalom túlnyúlik
             a diavetítés origóján.
             
             A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például
             transzformációk (például forgatás), vonalvastagság és illesztések,
             szöveg elrendezés és túlcsordulás, SmartArt geometria, valamint egyéb elrendezési hatások,
             amelyek befolyásolják a forma végleges megjelenését.
             
             A visszaadott határok nincsenek levágva a diavetítés téglalapjára.



### Lásd még
* osztály [`LegacyDiagram`](/slides/python-net/hu/aspose.slides/legacydiagram)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)