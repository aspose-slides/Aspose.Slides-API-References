---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona przy użyciu .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice obiektu, obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) reprezentujący wizualne granice obiektu w układzie współrzędnych slajdu



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje osiowo wyrównane granice całej zawartości wygenerowanej przez obiekt podczas renderowania w przestrzeni współrzędnych slajdu.

Te granice mogą różnić się od granic modelu obiektu ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height)) i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.

Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak przekształcenia (np. rotacja), szerokość i style linii, układ tekstu i przepełnienie, geometria SmartArt oraz inne efekty układu wpływające na końcowy wygląd renderowanego obiektu.

Zwrócone granice nie są przycinane do prostokąta slajdu.



### Zobacz także
* klasa [`OleObjectFrame`](/slides/python-net/pl/aspose.slides/oleobjectframe)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)