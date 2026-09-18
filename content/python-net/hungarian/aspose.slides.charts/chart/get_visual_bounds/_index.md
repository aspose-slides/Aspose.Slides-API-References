---
title: get_visual_bounds method
second_title: Aspose.Slides for Python .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
A forma vizuális határait adja vissza, amely a renderelt tartalom alapján kerül kiszámításra.

### Returns

A **aspose.slides.RectangleF**, amely a forma vizuális határait képviseli diavetítés koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

A visszaadott téglalap az összes tartalom tengelyekhez igazított határait ábrázolja
             amit a forma a renderelés során a diavetítés koordináta-térben állít elő.

             
             Ezek a határok eltérhetnek a forma modellhatáraitól
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom kiterjed
             a diavetítés origón túl.

             
             A vizuális határok figyelembe veszik a rendereléssel kapcsolatos tényezőket, például
             transzformációkat (például forgatás), vonalvastagságot és csatlakozásokat,
             szövegelrendezést és túlcsordulást, SmartArt geometriát, valamint egyéb elrendezési hatásokat
             amelyek befolyásolják a forma végső megjelenését.

             
             A visszaadott határok nincsenek levágva a diavetítés téglalapjára.



### See Also
* osztály [`Chart`](/slides/python-net/hu/aspose.slides.charts/chart)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)