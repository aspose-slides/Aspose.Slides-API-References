---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt **aspose.slides.RectangleF**, który reprezentuje wizualne granice kształtu
             w współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje granice wyrównane do osi całej zawartości
              wygenerowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.
             
              Te granice mogą różnić się od granic modelu kształtu
              ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
              [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
              i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza
              poza początek slajdu.
             
              Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak
              przekształcenia (na przykład obrót), szerokość i połączenia obrysu,
              układ i przepełnienie tekstu, geometria SmartArt oraz inne efekty układu,
              które wpływają na ostateczny wygląd renderowanego kształtu.
             
              Zwrócone granice nie są przycinane do prostokąta slajdu.



### Zobacz także
* klasa [`AutoShape`](/slides/python-net/pl/aspose.slides/autoshape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)