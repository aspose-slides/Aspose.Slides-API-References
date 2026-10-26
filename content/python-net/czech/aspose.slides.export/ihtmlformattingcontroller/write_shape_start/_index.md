---
title: write_shape_start method
second_title: Aspose.Slides pro Python přes .NET API
description: 
type: docs
url: /cs/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Volá se před vykreslením shape. Volá se jednou pro každý shape. Pokud tato funkce zapíše cokoli do generator, generování aktuálního obrázku snímku bude dokončeno, přidaný html fragment bude vložen a nový obrázek bude zahájen nad předchozím.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator) | Výstupní objekt. |
| shape | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) | Shape, který se má vykreslit. |



### Viz také
* třída [`IHtmlFormattingController`](/slides/python-net/cs/aspose.slides.export/ihtmlformattingcontroller)
* třída [`IHtmlGenerator`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator)
* třída [`IShape`](/slides/python-net/cs/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)