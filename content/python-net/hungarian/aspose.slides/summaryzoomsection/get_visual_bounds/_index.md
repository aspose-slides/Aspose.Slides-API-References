---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz a .NET API referencia alapján
description: 
type: docs
url: /hu/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Az alakzat vizuális határait adja vissza, amelyeket a megjelenített tartalom alapján számítanak ki.

### Visszatérési érték

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely az alakzat vizuális határait reprezentálja dia koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzés

A visszaadott téglalap a dia koordináta-rendszerben a renderelés során az alakzat által előállított összes tartalom tengely-alapú határait reprezentálja.  
Ezek a határok eltérhetnek az alakzat modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlnyúlik a dia eredetén.  
A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például a transzformációk (például forgatás), vonalvastagság és illesztések, szöveg elrendezés és túlcsordulás, SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják az alakzat végső megjelenését.  
A visszaadott határok nincsenek levágva a dia téglalapjára.

### Lásd még
* osztály [`SummaryZoomSection`](/slides/python-net/hu/aspose.slides/summaryzoomsection)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)