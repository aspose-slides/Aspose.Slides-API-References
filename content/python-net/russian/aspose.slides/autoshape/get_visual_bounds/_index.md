---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные на основе её отрисованного содержимого.

### Возвращаемое значение

Объект **aspose.slides.RectangleF**, представляющий визуальные границы фигуры в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Примечания

Возвращаемый прямоугольник представляет собой осево-ориентированные границы всего содержимого, создаваемого фигурой во время отрисовки в пространстве координат слайда.
            
Эти границы могут отличаться от модельных границ фигуры ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height)) и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала координат слайда.
            
Визуальные границы учитывают связанные с отрисовкой параметры, такие как трансформации (например, вращение), ширина обводки и соединения, верстка текста и переполнение, геометрию SmartArt и другие эффекты компоновки, влияющие на конечный вид отрисованной фигуры.
            
Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`AutoShape`](/slides/python-net/ru/aspose.slides/autoshape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)