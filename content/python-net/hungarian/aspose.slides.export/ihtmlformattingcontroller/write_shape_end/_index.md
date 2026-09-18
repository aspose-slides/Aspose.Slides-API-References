---
title: write_shape_end method
second_title: Aspose.Slides for Python a .NET API Referenciája
description: 
type: docs
url: /hu/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Az shape renderelése előtt hívódik. Minden shape esetén egyszer hívódik. Ha ez a függvény bármit ír a generator-ba, a jelenlegi diaképgenerálás befejeződik, a hozzáadott HTML-fragmentum beillesztésre kerül, és egy új kép indul a korábbi tetején.



```python
def write_shape_end(self, generator, shape):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator) | Kimeneti objektum. |
| shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | Az Shape, amelyik utoljára kerül renderelésre. |



### Lásd még
* osztály [`IHtmlFormattingController`](/slides/python-net/hu/aspose.slides.export/ihtmlformattingcontroller)
* osztály [`IHtmlGenerator`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator)
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)