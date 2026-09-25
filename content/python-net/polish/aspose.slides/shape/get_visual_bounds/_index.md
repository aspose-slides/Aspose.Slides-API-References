---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej treści.

### Zwraca

Obiekt [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) reprezentujący wizualne granice kształtu
             w współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje granice wyrównane do osi wszystkich treści
             wygenerowanych przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.
            
             Te granice mogą różnić się od modelowych granic kształtu
             ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
             i mogą zawierać ujemne współrzędne, jeśli renderowana treść wykracza
             poza początek slajdu.
            
             Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak
             przekształcenia (na przykład obrót), szerokość i łączenia linii,
             układ i przepełnienie tekstu, geometria SmartArt oraz inne efekty układu,
             które wpływają na ostateczny wygląd renderowanego kształtu.
            
             Zwrócone granice nie są przycinane do prostokąta slajdu.



### Zobacz także
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)