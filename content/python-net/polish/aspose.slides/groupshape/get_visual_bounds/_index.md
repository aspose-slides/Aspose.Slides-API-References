---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona via .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt **aspose.slides.RectangleF** reprezentujący wizualne granice kształtu
             w jednostkach współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt przedstawia granice wyrównane do osi całej zawartości
             generowanej przez kształt podczas renderowania w układzie współrzędnych slajdu.
            
             Te granice mogą różnić się od granic modelu kształtu
             ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
             i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza
             poza początek slajdu.
            
             Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak
             przekształcenia (np. rotacja), szerokość i połączenia obrysu,
             układ i przepełnienie tekstu, geometria SmartArt oraz inne efekty układu
             wpływające na ostateczny wygląd renderowanego kształtu.
            
             Zwrócone granice nie są przycięte do prostokąta slajdu.



### Zobacz także
* klasa [`GroupShape`](/slides/python-net/pl/aspose.slides/groupshape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)