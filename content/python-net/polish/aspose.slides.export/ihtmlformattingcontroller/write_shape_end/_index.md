---
title: write_shape_end method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Wywoływane przed renderowaniem kształtu. Wywoływane raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, bieżące generowanie obrazu slajdu zostanie zakończone, wstawiony zostanie dodany fragment HTML i nowy obraz zostanie rozpoczęty na szczycie poprzedniego.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/pl/aspose.slides.export/ihtmlgenerator) | Obiekt wyjściowy. |
| shape | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) | Kształt renderowany jako ostatni. |



### Zobacz także
* klasa [`IHtmlFormattingController`](/slides/python-net/pl/aspose.slides.export/ihtmlformattingcontroller)
* klasa [`IHtmlGenerator`](/slides/python-net/pl/aspose.slides.export/ihtmlgenerator)
* klasa [`IShape`](/slides/python-net/pl/aspose.slides/ishape)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)