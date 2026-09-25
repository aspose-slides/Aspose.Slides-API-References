---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona poprzez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Zwraca wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) który reprezentuje wizualne granice kształtu
             w współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje granice osiowo wyrównane całej zawartości wygenerowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.

Te granice mogą różnić się od granic modelu kształtu ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height)) i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.

Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak transformacje (np. obrót), szerokość i połączenia obramowań, układ tekstu i przepełnienie, geometrię SmartArt oraz inne efekty układu wpływające na ostateczny wygląd renderowanego kształtu.

Zwrócone granice nie są przycinane do prostokąta slajdu.



### Zobacz także
* klasa [`SummaryZoomSection`](/slides/python-net/pl/aspose.slides/summaryzoomsection)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)