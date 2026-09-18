---
title: get_visual_bounds method
second_title: Aspose.Slides a Pythonhoz .NET API Referenciája
description: 
type: docs
url: /hu/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lekéri az alakzat vizuális határait, amelyek a megjelenített tartalma alapján számítottak.

### Visszatér

Egy **aspose.slides.RectangleF**, amely az alakzat vizuális határait ábrázolja a dia koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzés

A visszaadott téglalap a diagram koordináta térben az alakzat által a renderelés során előállított teljes tartalom tengelyigazított határait képviseli.

Ezek a határok eltérhetnek az alakzat modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)), és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom a dia eredetén túlra nyúlik.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például az átalakítások (például forgatás), a vonalvastagság és csatlakozások, a szöveg elrendezése és túlcsordulása, a SmartArt geometria, valamint egyéb elrendezési hatások, amelyek befolyásolják az alakzat végső megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapra.



### Lásd még
* osztály [`Connector`](/slides/python-net/hu/aspose.slides/connector)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)