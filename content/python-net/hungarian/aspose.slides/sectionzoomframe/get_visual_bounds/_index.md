---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
A forma vizuális határolóit adja vissza, amelyeket a megjelenített tartalma alapján számítanak ki.

### Visszatérési érték

Egy **aspose.slides.RectangleF**, amely a forma vizuális határolóit jelöli
             dia koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzés

A visszakapott téglalap a forma által a megjelenítés során előállított összes tartalom tengelyhez igazított határait ábrázolja
             dia koordináta térben.
            
             Ezek a határok eltérhetnek a forma modellhatáraitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom a dia eredetén túlterjed.
            
             A vizuális határok figyelembe veszik a megjelenítéshez kapcsolódó szempontokat, például
             átalakításokat (például forgatás), vonalvastagságot és illesztéseket,
             szöveg elrendezését és túlcsordulását, SmartArt geometriát és egyéb elrendezési hatásokat,
             amelyek befolyásolják a forma végső megjelenését.
            
             A visszakapott határok nincsenek levágva a dia téglalapjára.



### Lásd még
* osztály [`SectionZoomFrame`](/slides/python-net/hu/aspose.slides/sectionzoomframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)