---
title: write_shape_start method
second_title: Aspose.Slides a Python számára .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
A shape megjelenítése előtt hívódik. Minden egyes shape esetén egyszer hívódik. Ha ez a függvény bármit ír a generatorba, a jelenlegi dia képgenerálás befejeződik, a hozzáadott html töredék beillesztésre kerül, és egy új kép kezdődik az előző tetején.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator) | Kimeneti objektum. |
| shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | Alakzat, amely renderelésre készül. |



### Lásd még
* osztály [`EmbedAllFontsHtmlController`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller)
* osztály [`IHtmlGenerator`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator)
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)