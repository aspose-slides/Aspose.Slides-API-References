---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona przez .NET - Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) reprezentujący wizualne granice kształtu w współrzędnych slajdu



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje wyrównane do osi granice całej zawartości generowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.

Te granice mogą różnić się od granic modelu kształtu ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height)) i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.

Wizualne granice uwzględniają elementy związane z renderowaniem, takie jak transformacje (np. obrót), szerokość i łączenia linii, układ i przepełnienie tekstu, geometrię SmartArt oraz inne efekty układu wpływające na ostateczny wygląd renderowanego kształtu.

Zwrócone granice nie są przycinane do prostokąta slajdu.



### Zobacz także
* klasa [`SmartArtShape`](/slides/python-net/pl/aspose.slides.smartart/smartartshape)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides.smartart`](/slides/python-net/pl/aspose.slides.smartart)
* biblioteka [`Aspose.Slides`](/slides/python-net)