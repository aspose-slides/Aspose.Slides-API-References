---
title: write_shape_end method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
A shape renderelése előtt hívódik. Minden shape-ra egyszer hívódik. Ha ez a függvény bármit ír a generatorba, az aktuális dia kép generálása befejeződik, a hozzáadott HTML töredék beillesztésre kerül, és egy új kép lesz elindítva az előző tetején.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator) | Kimeneti objektum. |
| shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | Az utoljára renderelt shape. |



### Lásd még
* osztály [`EmbedAllFontsHtmlController`](/slides/python-net/hu/aspose.slides.export/embedallfontshtmlcontroller)
* osztály [`IHtmlGenerator`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator)
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)