---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona poprzez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
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
             i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.

             Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak
             przekształcenia (np. rotacja), szerokość i połączenia linii,
             układ i przepełnienie tekstu, geometria SmartArt oraz inne efekty układu
             wpływające na końcowy wygląd renderowanego kształtu.

             Zwrócone granice nie są przycięte do prostokąta slajdu.



### Zobacz także
* klasa [`Chart`](/slides/python-net/pl/aspose.slides.charts/chart)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)