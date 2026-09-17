---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные на основе её отрисованного содержимого.

### Возвращаемое значение

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Примечания
Возвращаемый прямоугольник представляет осно-выравнённые границы всего содержимого
             создаваемого фигурой во время отрисовки в координатном пространстве слайда.

Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала слайда.

Визуальные границы учитывают связанные с отрисовкой аспекты, такие как
transformations (for example, rotation), stroke width and joins,
text layout and overflow, SmartArt geometry, and other layout effects
that influence the final rendered appearance of the shape.

Возвращённые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`SummaryZoomSection`](/slides/python-net/ru/aspose.slides/summaryzoomsection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)