---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona poprzez .NET referencja API
description: 
type: docs
url: /pl/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczane na podstawie jego renderowanej zawartości.

### Zwraca

Obiekt [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef), który reprezentuje wizualne granice kształtu w współrzędnych slajdu.

```python
def get_visual_bounds(self):
    ...
```

### Uwagi
The returned rectangle represents the axis-aligned bounds of all content
            produced by the shape during rendering in slide coordinate space.
           
            These bounds may differ from the shape's model bounds
            ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
            and may contain negative coordinates if the rendered content extends
            beyond the slide origin.
           
            Granice wizualne uwzględniają aspekty związane z renderowaniem, takie jak przekształcenia (na przykład obrócenie), szerokość i łączenia obrysu, układ i przepełnienie tekstu, geometria SmartArt oraz inne efekty układu, które wpływają na ostateczny wygląd renderowanego kształtu.
           
            Zwrócone granice nie są przycięte do prostokąta slajdu.

### Zobacz też
* klasa [`AudioFrame`](/slides/python-net/pl/aspose.slides/audioframe)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)