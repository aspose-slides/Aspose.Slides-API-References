---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekéri a forma vizuális határait, amelyeket a megjelenített tartalma alapján számítanak.

### Visszatérési érték

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait ábrázolja a dia koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések
A visszaadott téglalap ábrázolja az összes tartalom tengelyre igazított határait
             amelyet a forma a megjelenítés során a dia koordináta térben hoz létre.
             
             Ezek a határok eltérhetnek a forma modell határaitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom kiterjed
             a dia origója túlra.
             
             A vizuális határok figyelembe veszik a megjelenítéshez kapcsolódó szempontokat, például
             átalakításokat (például forgatás), vonalvastagságot és illesztéseket,
             szöveg elrendezést és túlcsordulást, SmartArt geometriát, valamint egyéb elrendezési hatásokat
             amelyek befolyásolják a forma végső megjelenő megjelenését.
             
             A visszaadott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`SummaryZoomFrame`](/slides/python-net/hu/aspose.slides/summaryzoomframe)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)