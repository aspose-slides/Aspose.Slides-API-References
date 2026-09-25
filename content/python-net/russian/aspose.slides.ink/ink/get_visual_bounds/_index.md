---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого.

### Returns

Объект [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef), представляющий визуальные границы фигуры в координатах слайда.

```python
def get_visual_bounds(self):
    ...
```

### Remarks

Возвращаемый прямоугольник представляет собой выровненные по осям границы всего содержимого, создаваемого фигурой во время отрисовки в координатном пространстве слайда.

Эти границы могут отличаться от границ модели фигуры ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height)) и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала слайда.

В визуальные границы учитываются связанные с отрисовкой аспекты, такие как трансформации (например, вращение), толщина и соединения линий, компоновка текста и переполнение, геометрия SmartArt и другие эффекты расположения, влияющие на окончательный визуальный вид фигуры.

Возвращаемые границы не обрезаются до прямоугольника слайда.

### See Also
* класс [`Ink`](/slides/python-net/ru/aspose.slides.ink/ink)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides.ink`](/slides/python-net/ru/aspose.slides.ink)
* библиотека [`Aspose.Slides`](/slides/python-net)