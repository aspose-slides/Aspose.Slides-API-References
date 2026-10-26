---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lekéri a forma megjelenített tartalma alapján kiszámított vizuális határait.

### Returns

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait ábrázolja
             diavetítés koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Az eredményül kapott téglalap a forma által a renderelés során előállított összes tartalom
             tengely-alapú határait jelenti a dia koordináta térben.
            
Ezek a határok eltérhetnek a forma modellhatáraitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik a dia origóján.
            
A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például
             transzformációk (például forgatás), vonalvastagság és illesztések,
             szövegelrendezés és túlcsordulás, SmartArt geometria, valamint egyéb elrendezési hatások,
             amelyek befolyásolják a forma végső megjelenését.
            
A visszaadott határok nincsenek levágva a dia téglalapra.



### Lásd még
* osztály [`LegacyDiagram`](/slides/python-net/hu/aspose.slides/legacydiagram)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)