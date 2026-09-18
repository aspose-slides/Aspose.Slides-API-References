---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona poprzez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt **aspose.slides.RectangleF**, który reprezentuje wizualne granice kształtu w współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje osiowo wyrównane granice całej zawartości generowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.

Te granice mogą różnić się od granic modelu kształtu ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height)) i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wychodzi poza początek slajdu.

Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak przekształcenia (np. obrót), szerokość i połączenia obrysów, układ i przepełnienie tekstu, geometrię SmartArt oraz inne efekty układu wpływające na ostateczny wygląd renderowanego kształtu.

Zwrócone granice nie są przycinane do prostokąta slajdu.



### Zobacz także
* klasa [`SmartArt`](/slides/python-net/pl/aspose.slides.smartart/smartart)
* moduł [`aspose.slides.smartart`](/slides/python-net/pl/aspose.slides.smartart)
* biblioteka [`Aspose.Slides`](/slides/python-net)