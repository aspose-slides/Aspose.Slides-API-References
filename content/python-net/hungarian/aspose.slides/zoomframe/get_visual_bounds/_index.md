---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozáson keresztül
description: 
type: docs
url: /hu/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A forma vizuális határait a megjelenített tartalom alapján számítja ki.

### Visszatérési érték

A **aspose.slides.RectangleF**, amely a forma vizuális határait ábrázolja diavetítés koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap a forma által a renderelés során előállított összes tartalom tengely-alapú határait jeleníti meg a diavetítés koordinátaterében.
            
Ezek a határok eltérhetnek a forma modell határaitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom túlnyúlik a dia eredetén.
            
A vizuális határok figyelembe veszik a rendereléshez kapcsolódó aspektusokat, például a transzformációkat (mint például a forgatás), a vonalvastagságot és illeszkedéseket, a szövegelrendezést és túlcsordulást, a SmartArt geometriai alakzatát, valamint egyéb elrendezési hatásokat, amelyek befolyásolják a forma végső megjelenését.
            
A visszaadott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`ZoomFrame`](/slides/python-net/hu/aspose.slides/zoomframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)