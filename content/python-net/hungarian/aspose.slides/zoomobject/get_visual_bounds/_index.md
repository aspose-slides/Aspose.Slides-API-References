---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekéri a forma vizuális határait, amelyeket a renderelt tartalom alapján számítanak ki.

### Returns
A [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef) amely a forma vizuális határait ábrázolja
             diavetítés koordinátáiban.

```python
def get_visual_bounds(self):
    ...
```

### Remarks
A visszaadott téglalap a teljes tartalom tengelyekhez igazított határait jelöli,
             amelyet a forma a renderelés során a diavetítés koordinátarendszerében hoz létre.
            
             Ezek a határok eltérhetnek a forma modellhatáraitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlmutat a dia origóján.
            
             A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, például
             transzformációkat (például elforgatás), vonalvastagságot és csatlakozásokat,
             szöveg elrendezést és túlcsordulást, SmartArt geometriát és egyéb elrendezési hatásokat,
             amelyek befolyásolják a forma végső megjelenését.
            
             A visszaadott határokat nem vágják le a dia téglalapjára.

### See Also
* osztály [`ZoomObject`](/slides/python-net/hu/aspose.slides/zoomobject)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)