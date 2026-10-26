---
title: write_shape_end method
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Voláno před vykreslením shape. Voláno jednou pro každý shape. Pokud tato funkce zapíše cokoliv do generator, aktuální generování obrázku snímku bude dokončeno, přidaný HTML fragment bude vložen a nový obrázek bude zahájen nad předchozím.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator) | Výstupní objekt. |
| shape | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) | Tvar, který je vykreslen jako poslední. |



### Viz také
* třída [`IHtmlFormattingController`](/slides/python-net/cs/aspose.slides.export/ihtmlformattingcontroller)
* třída [`IHtmlGenerator`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator)
* třída [`IShape`](/slides/python-net/cs/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)