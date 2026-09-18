---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A alakzat megjelenített tartalma alapján kiszámított vizuális határvonalakat adja vissza.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely a alakzat vizuális határvonalait ábrázolja diák koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzés

A visszaadott téglalap az összes tartalom tengelyhez igazított határvonalait ábrázolja, amelyet az alakzat a renderelés során a diák koordináta térben állít elő.

Ezek a határvonalak eltérhetnek az alakzat modellhatárától
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom kiterjed
             a diák origóján túlra.

A vizuális határvonalak figyelembe veszik a rendereléshez kapcsolódó szempontokat, mint például
             a transzformációk (például forgatás), a vonalvastagság és illesztések,
             a szöveg elrendezése és túlcsordulása, a SmartArt geometria, valamint egyéb elrendezési hatások,
             amelyek befolyásolják az alakzat végső megjelenését.

A visszaadott határvonalak nincsenek levágva a diák téglalapjára.



### Lásd még
* osztály [`InkActions`](/slides/python-net/hu/aspose.slides.ink/inkactions)
* modul [`aspose.slides.ink`](/slides/python-net/hu/aspose.slides.ink)
* könyvtár [`Aspose.Slides`](/slides/python-net)