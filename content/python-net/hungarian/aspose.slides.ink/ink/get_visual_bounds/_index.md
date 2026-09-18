---
title: get_visual_bounds method
second_title: Aspose.Slides Python-hoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A megjelenített tartalom alapján kiszámított alakzat vizuális korlátait adja vissza.

### Visszatérési érték

A **aspose.slides.RectangleF** amely a dia koordinátáiban az alakzat vizuális korlátait ábrázolja.

```python
def get_visual_bounds(self):
    ...
```

### Megjegyzések
A visszaadott téglalap reprezentálja az összes tartalom tengelyigazított korlátait
             amelyet az alakzat generál a renderelés során a dia koordináta-térben.

             Ezek a korlátok eltérhetnek az alakzat modellkorlátjától
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom kiterjed
             a dia eredete utánra.

             A vizuális korlátok figyelembe veszik a rendereléshez kapcsolódó szempontokat, például
             transzformációkat (például forgás), vonalszélességet és illesztéseket,
             szövegelrendezést és túlcsordulást, SmartArt geometriát, és egyéb elrendezési hatásokat,
             amelyek befolyásolják az alakzat végső renderelt megjelenését.

             A visszaadott korlátok nincsenek levágva a dia téglalapra.

### Lásd még
* osztály [`Ink`](/slides/python-net/hu/aspose.slides.ink/ink)
* modul [`aspose.slides.ink`](/slides/python-net/hu/aspose.slides.ink)
* könyvtár [`Aspose.Slides`](/slides/python-net)