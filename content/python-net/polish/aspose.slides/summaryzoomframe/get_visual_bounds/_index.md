---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET API
description: 
type: docs
url: /pl/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice obiektu obliczone na podstawie jego renderowanej zawartości.

### Zwraca
[`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) reprezentujący wizualne granice obiektu w współrzędnych slajdu.

```python
def get_visual_bounds(self):
    ...
```

### Uwagi
Zwrócony prostokąt reprezentuje osowo wyrównane granice całej zawartości
generowanej przez obiekt podczas renderowania w przestrzeni współrzędnych slajdu.

Te granice mogą różnić się od granic modelu obiektu
([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza
poza początek slajdu.

Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak
transformacje (na przykład obrót), szerokość i połączenia linii kreski,
układ tekstu i przepełnienie, geometria SmartArt oraz inne efekty układu,
które wpływają na ostateczny wygląd renderowanego obiektu.

Zwrócone granice nie są przycięte do prostokąta slajdu.

### Zobacz także
* klasa [`SummaryZoomFrame`](/slides/python-net/pl/aspose.slides/summaryzoomframe)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)