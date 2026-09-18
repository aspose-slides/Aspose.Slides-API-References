---
title: get_visual_bounds method
second_title: Aspose.Slides Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
A forma megjelenített tartalma alapján számított vizuális határokat adja vissza.

### Visszatérési érték

A **aspose.slides.RectangleF**, amely a forma vizuális határait jelöli a diák koordinátáiban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések

A visszaadott téglalap az összes tartalom tengelyekhez igazított határait mutatja
            a forma által a megjelenítés során a diák koordinátatérben előállított elemeket.

            Ezek a határok eltérhetnek a forma modellhatáraitól
            ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
            és tartalmazhatnak negatív koordinátákat, ha a megjelenített tartalom túlnyúlik
            a diák origón túl.

            A vizuális határok figyelembe veszik a rendereléshez kapcsolódó szempontokat, például
            transzformációkat (például forgatás), vonalvastagságot és illesztéseket,
            szövegelrendezést és túlfutást, SmartArt geometriát, valamint egyéb elrendezési hatásokat,
            amelyek befolyásolják a forma végső megjelenését.

            A visszaadott határok nincsenek levágva a dia téglalapjára.


### Lásd még
* osztály [`VideoFrame`](/slides/python-net/hu/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)