---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi
Zwrócony prostokąt reprezentuje wyrównane względem osi granice całej zawartości
             wygenerowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.
             
             Te granice mogą różnić się od granic modelu kształtu
             ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
             i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza
             poza początek slajdu.
             
             Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak
             przekształcenia (na przykład, rotacja), szerokość i połączenia linii,
             układ i przepełnienie tekstu, geometria SmartArt oraz inne efekty układu,
             które wpływają na ostateczny wygląd renderowanego kształtu.
             
             Zwrócone granice nie są przycinane do prostokąta slajdu.



### Zobacz także
* klasa [`PictureFrame`](/slides/python-net/pl/aspose.slides/pictureframe)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)