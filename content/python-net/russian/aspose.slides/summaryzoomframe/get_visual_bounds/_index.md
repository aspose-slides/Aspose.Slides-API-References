---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого.

### Returns
Возвращает объект [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef), представляющий визуальные границы фигуры в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Remarks
Возвращаемый прямоугольник представляет собой осно-ориентированные границы всего содержимого, созданного фигурой во время рендеринга, в координатах слайда.

Эти границы могут отличаться от модельных границ фигуры ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height)) и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала слайда.

Визуальные границы учитывают связанные с отрисовкой аспекты, такие как трансформации (например, вращение), ширина обводки и соединения, верстка текста и переполнение, геометрия SmartArt и другие эффекты расположения, влияющие на окончательный отрисованный вид фигуры.

Возвращаемые границы не обрезаются до прямоугольника слайда.



### See Also
* класс [`SummaryZoomFrame`](/slides/python-net/ru/aspose.slides/summaryzoomframe)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)