---
title: get_visual_bounds method
second_title: Aspose.Slides Python API referencia .NET-en keresztül
description: 
type: docs
url: /hu/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Visszaadja a forma renderelt tartalma alapján számított vizuális határait.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely a forma vizuális határait ábrázolja a dia koordinátáiban.

```python
def get_visual_bounds(self):
    ...
```

### Megjegyzések

A visszaadott téglalap a dia koordináta térben a forma által a renderelés során előállított összes tartalom tengelyekhez igazított határait képviseli.

Ezek a határok eltérhetnek a forma modellhatáraitól ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height)) és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom a dia origón kívülre nyúlik.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó tényezőket, például a transzformációkat (például forgatás), a vonalvastagságot és csatlakozásokat, a szöveg elrendezését és túlcsordulását, a SmartArt geometriáját, valamint egyéb elrendezési hatásokat, amelyek befolyásolják a forma végső megjelenését.

A visszaadott határok nincsenek levágva a dia téglalapjára.

### Lásd még
* osztály [`AudioFrame`](/slides/python-net/hu/aspose.slides/audioframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)