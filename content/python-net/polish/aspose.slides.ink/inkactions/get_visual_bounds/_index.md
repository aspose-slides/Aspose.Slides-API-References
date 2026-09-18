---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Zwraca wizualne granice kształtu obliczone na podstawie renderowanej zawartości.

### Zwraca

Obiekt **aspose.slides.RectangleF**, który reprezentuje wizualne granice kształtu w współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje granice wyrównane do osi całej zawartości wygenerowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.

Te granice mogą różnić się od granic modelowych kształtu ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height)) i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.

Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak przekształcenia (na przykład obrót), szerokość i połączenia obrysu, układ i przepełnienie tekstu, geometria SmartArt oraz inne efekty układu wpływające na ostateczny wygląd kształtu po renderowaniu.

Zwrócone granice nie są przycięte do prostokąta slajdu.



### Zobacz także
* klasa [`InkActions`](/slides/python-net/pl/aspose.slides.ink/inkactions)
* moduł [`aspose.slides.ink`](/slides/python-net/pl/aspose.slides.ink)
* biblioteka [`Aspose.Slides`](/slides/python-net)