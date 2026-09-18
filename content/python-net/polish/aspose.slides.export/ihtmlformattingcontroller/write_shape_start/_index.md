---
title: write_shape_start method
second_title: Aspose.Slides dla Pythona - odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Wywoływane przed renderowaniem kształtu. Wywoływane raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, bieżące generowanie obrazu slajdu zostanie zakończone, dodany fragment HTML zostanie wstawiony, a nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.

```python
def write_shape_start(self, generator, shape):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/pl/aspose.slides.export/ihtmlgenerator) | Obiekt wyjściowy. |
| shape | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) | Kształt, który ma zostać wyrenderowany. |

### Zobacz także
* klasa [`IHtmlFormattingController`](/slides/python-net/pl/aspose.slides.export/ihtmlformattingcontroller)
* klasa [`IHtmlGenerator`](/slides/python-net/pl/aspose.slides.export/ihtmlgenerator)
* klasa [`IShape`](/slides/python-net/pl/aspose.slides/ishape)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)