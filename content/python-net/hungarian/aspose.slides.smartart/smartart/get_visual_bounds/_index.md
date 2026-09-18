---
title: get_visual_bounds method
second_title: Aspose.Slides a Python számára .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A shape vizuális határait adja vissza, a renderelt tartalom alapján kiszámítva.

### Returns

A **aspose.slides.RectangleF**, amely a shape vizuális határait jelöli a slide koordinátáiban
             a slide koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

A visszaadott téglalap a shape által a renderelés során előállított összes tartalom tengely-alapú határait jelöli a slide koordináta-térben.
            
             Ezek a határok eltérhetnek a shape modell határaitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom a slide eredetének
             túlra nyúlik.
            
             A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például a transzformációk (például forgatás), vonalvastagság és elírások, szövegelrendezés és túlfutás, SmartArt geometria és egyéb elrendezési hatások,
             amelyek befolyásolják a shape végső megjelenését.
            
             A visszaadott határok nincsenek levágva a slide téglalapra.



### See Also
* osztály [`SmartArt`](/slides/python-net/hu/aspose.slides.smartart/smartart)
* modul [`aspose.slides.smartart`](/slides/python-net/hu/aspose.slides.smartart)
* könyvtár [`Aspose.Slides`](/slides/python-net)