---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona przez .NET API Referencja
description: 
type: docs
url: /pl/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt **aspose.slides.RectangleF**, który reprezentuje wizualne granice kształtu w współrzędnych slajdu
             w przestrzeni współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi
The returned rectangle represents the axis-aligned bounds of all content
             Zwrócony prostokąt reprezentuje wyrównane do osi granice całej zawartości wygenerowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.
            
             These bounds may differ from the shape's model bounds
             Te granice mogą różnić się od granic modelu kształtu ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
             i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.
            
             The visual bounds take into account rendering-related aspects such as
             Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak przekształcenia (na przykład rotacja), szerokość i połączenia obramowania, układ i przepełnienie tekstu, geometrię SmartArt oraz inne efekty układu, które wpływają na ostateczny wygląd renderowanego kształtu.
            
             The returned bounds are not clipped to the slide rectangle.
             Zwrócone granice nie są przycinane do prostokąta slajdu.



### Zobacz także
* klasa [`SectionZoomFrame`](/slides/python-net/pl/aspose.slides/sectionzoomframe)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)