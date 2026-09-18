---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona – odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt **aspose.slides.RectangleF** reprezentujący wizualne granice kształtu
             w współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje wyrównane do osi granice całej zawartości wygenerowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.
            
            Te granice mogą różnić się od modelowych granic kształtu
            ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
            i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza
            poza początek slajdu.
            
            Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak
            przekształcenia (na przykład, obrót), szerokość i połączenia pędzla,
            układ i przepełnienie tekstu, geometria SmartArt oraz inne efekty układu,
            które wpływają na ostateczny wygląd renderowanego kształtu.
            
            Zwrócone granice nie są przycięte do prostokąta slajdu.



### Zobacz także
* klasa [`VideoFrame`](/slides/python-net/pl/aspose.slides/videoframe)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)