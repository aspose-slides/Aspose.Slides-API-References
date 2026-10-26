---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Zwraca wizualne granice obiektu obliczone na podstawie jego renderowanej zawartości.

### Returns

Obiekt [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) reprezentujący wizualne granice obiektu w współrzędnych slajdu



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Zwrócony prostokąt reprezentuje granice wyrównane do osi całej zawartości
             wytworzonej przez obiekt podczas renderowania w przestrzeni współrzędnych slajdu.
            
             Te granice mogą różnić się od modelowych granic obiektu
             ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
             i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość rozciąga się
             poza początkiem slajdu.
            
             Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak
             transformacje (na przykład obrót), szerokość obrysu i połączenia,
             układ tekstu i przepełnienie, geometria SmartArt oraz inne efekty układu
             które wpływają na ostateczny wygląd renderowanego obiektu.
            
             Zwrócone granice nie są przycięte do prostokąta slajdu.



### Zobacz także
* klasa [`VideoFrame`](/slides/python-net/pl/aspose.slides/videoframe)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)