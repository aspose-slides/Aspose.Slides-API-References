---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Pobiera granice wizualne kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) reprezentujący granice wizualne kształtu w współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje ograniczenia wyrównane do osi dla całej zawartości
             wygenerowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.

             Te ograniczenia mogą różnić się od ograniczeń modelu kształtu
             ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
             i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza
             poza początek slajdu.

             Granice wizualne uwzględniają aspekty związane z renderowaniem, takie jak
             przekształcenia (na przykład obrót), szerokość i łączenia linii,
             układ tekstu i przepełnienie, geometria SmartArt oraz inne efekty układu,
             które wpływają na ostateczny wygląd renderowanego kształtu.

             Zwrócone ograniczenia nie są przycinane do prostokąta slajdu.



### Zobacz także
* klasa [`ZoomObject`](/slides/python-net/pl/aspose.slides/zoomobject)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)