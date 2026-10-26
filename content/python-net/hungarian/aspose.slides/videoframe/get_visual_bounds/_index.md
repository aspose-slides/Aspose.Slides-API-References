---
title: get_visual_bounds method
second_title: Aspose.Slides a Python számára .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lekéri a forma vizuális határait, amelyeket a renderelt tartalom alapján számítanak ki.

### Visszatérési érték

Egy [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef), amely a forma vizuális határait jelöli
             diavetítés koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzés

A visszaadott téglalap a forma által a renderelés során előállított összes tartalom tengely-igazított határait jelöli a diavetítés koordináta térben.
            
             Ezek a határok eltérhetnek a forma modell-határaitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom a diavetítés origója után terjed.
            
             A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, például átalakítások (például forgatás), vonalvastagság és csatlakozások, szöveg elrendezése és túlcsordulása, SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják a forma végső megjelenését.
            
             A visszaadott határok nem vannak levágva a diavetítés téglalapjára.



### Lásd még
* osztály [`VideoFrame`](/slides/python-net/hu/aspose.slides/videoframe)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)