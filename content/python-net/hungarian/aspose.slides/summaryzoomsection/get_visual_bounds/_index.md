---
title: get_visual_bounds method
second_title: Aspose.Slides a Python-hoz a .NET API-n keresztül
description: 
type: docs
url: /hu/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A forma vizuális határait adja vissza, amely a renderelt tartalom alapján számítódik ki.

### Visszatérési érték
Egy **aspose.slides.RectangleF**, amely a forma vizuális határait jelöli
             a dia koordinátáiban.

```python
def get_visual_bounds(self):
    ...
```

### Megjegyzések
A visszaadott téglalap az összes tartalom tengely-igazított határait jelöli
             amelyet a forma a renderelés során a dia koordináta-térben hoz létre.

             Ezek a határok eltérhetnek a forma modell-határaitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik
             a dia origón.

             A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például a transzformációk (például forgatás), a vonalvastagság és illeszkedések, a szövegelrendezés és túlcsordulás, a SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végső megjelenését.

             A visszaadott határok nincsenek levágva a dia téglalapjára.

### Lásd még
* osztály [`SummaryZoomSection`](/slides/python-net/hu/aspose.slides/summaryzoomsection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)