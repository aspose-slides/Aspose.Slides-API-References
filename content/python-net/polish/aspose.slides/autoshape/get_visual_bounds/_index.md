---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona poprzez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczane z jego renderowanej zawartości.

### Returns

Obiekt [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) reprezentujący wizualne granice kształtu w współrzędnych slajdu



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Zwrócony prostokąt reprezentuje granice wyrównane do osi całej zawartości wytworzonej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.

Te granice mogą różnić się od granic modelu kształtu ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height)) i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.

Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak transformacje (na przykład rotacja), szerokość i połączenia obrysu, układ tekstu i przepełnienie, geometria SmartArt oraz inne efekty układu wpływające na ostateczny wygląd renderowanego kształtu.

Zwrócone granice nie są przycinane do prostokąta slajdu.



### See Also
* klasa [`AutoShape`](/slides/python-net/pl/aspose.slides/autoshape)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)