---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona via .NET referencja API
description: 
type: docs
url: /pl/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Zwraca wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt **aspose.slides.RectangleF**, który reprezentuje wizualne granice kształtu w układzie współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje prostopadłe granice całej zawartości wygenerowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.

Te granice mogą różnić się od granic modelu kształtu ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height)) i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.

Wizualne granice uwzględniają aspekt związany z renderowaniem, taki jak przekształcenia (np. obrót), szerokość i połączenia obrysu, układ tekstu i przepełnienie, geometria SmartArt oraz inne efekty układu wpływające na ostateczny wygląd renderowanego kształtu.

Zwrócone granice nie są przycinane do prostokąta slajdu.



### Zobacz także
* klasa [`Ink`](/slides/python-net/pl/aspose.slides.ink/ink)
* moduł [`aspose.slides.ink`](/slides/python-net/pl/aspose.slides.ink)
* biblioteka [`Aspose.Slides`](/slides/python-net)