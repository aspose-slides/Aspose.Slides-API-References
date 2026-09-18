---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczone z jego renderowanej zawartości.

### Returns
Obiekt **aspose.slides.RectangleF** reprezentujący wizualne granice kształtu w współrzędnych slajdu.



```python
def get_visual_bounds(self):
    ...
```


### Remarks
Zwrócony prostokąt reprezentuje ograniczenia osiowo-wyrównane całej zawartości generowanej przez kształt podczas renderowania w układzie współrzędnych slajdu.

Te ograniczenia mogą różnić się od ograniczeń modelu kształtu ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height)) i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.

Wizualne granice uwzględniają aspekty związane z renderowaniem, takie jak transformacje (na przykład obrót), szerokość i połączenia obrysu, układ i przepełnienie tekstu, geometrię SmartArt oraz inne efekty układu wpływające na ostateczny wygląd renderowanego kształtu.

Zwrócone granice nie są przycinane do prostokąta slajdu.



### See Also
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)