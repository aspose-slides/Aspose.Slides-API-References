---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого.

### Возвращаемое значение

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.

```python
def get_visual_bounds(self):
    ...
```

### Примечания

Возвращаемый прямоугольник представляет собой осесимметричные границы всего содержимого
             генерируемого фигурой во время отрисовки в координатном пространстве слайда.

Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала слайда.

Визуальные границы учитывают связанные с рендерингом аспекты, такие как
             трансформации (например, вращение), ширина и соединения штрихов,
             верстка текста и переполнение, геометрия SmartArt и другие эффекты компоновки,
             влияющие на окончательный вид отрисованной фигуры.

Возвращаемые границы не обрезаются до прямоугольника слайда.

### См. также
* класс [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)