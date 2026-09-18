---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Pobiera wizualne ograniczenia kształtu obliczone na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt **aspose.slides.RectangleF** reprezentujący wizualne ograniczenia kształtu
             w współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi

Zwrócony prostokąt reprezentuje ograniczenia osiowo wyrównane całej zawartości
             generowanej przez kształt podczas renderowania w układzie współrzędnych slajdu.
            
             Te ograniczenia mogą różnić się od ograniczeń modelu kształtu
             ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
             i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.
            
             Wizualne ograniczenia uwzględniają aspekty związane z renderowaniem, takie jak
             przekształcenia (np. obrót), szerokość i połączenia linii,
             układ i przepełnienie tekstu, geometria SmartArt oraz inne efekty układu,
             które wpływają na ostateczny wygląd renderowanego kształtu.
            
             Zwrócone ograniczenia nie są przycięte do prostokąta slajdu.



### Zobacz także
* klasa [`SmartArtShape`](/slides/python-net/pl/aspose.slides.smartart/smartartshape)
* moduł [`aspose.slides.smartart`](/slides/python-net/pl/aspose.slides.smartart)
* biblioteka [`Aspose.Slides`](/slides/python-net)