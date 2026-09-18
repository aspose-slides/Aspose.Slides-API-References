---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lekéri a alakzat vizuális határolóját, amely a megjelenített tartalom alapján kerül kiszámításra.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely a alakzat vizuális határolóját jelöli diavetítés koordinátákban.


```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések
A visszaadott téglalap az összes tartalom tengely-igazított határolóit ábrázolja
amelyet az alakzat a renderelés során hoz létre a diavetítés koordinátertérben.

Ezek a határolók eltérhetnek az alakzat modell határától
([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom meghaladja
a dia eredetét.

A vizuális határolók figyelembe veszik a rendereléshez kapcsolódó szempontokat, például
transzformációkat (például forgatás), vonalvastagságot és illesztéseket,
szöveg elrendezést és túlcsordulást, SmartArt geometriát, valamint egyéb elrendezési hatásokat
amelyek befolyásolják az alakzat végső megjelenését.

A visszaadott határolók nincsenek levágva a dia téglalapjára.


### Lásd még
* osztály [`Table`](/slides/python-net/hu/aspose.slides/table)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)