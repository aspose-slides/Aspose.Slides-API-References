---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные на основе её отображаемого содержимого.

### Возвращаемое значение
Объект [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef), представляющий визуальные границы фигуры
             в координатах слайда.

```python
def get_visual_bounds(self):
    ...
```

### Примечание
Возвращаемый прямоугольник представляет осно-ориентированные границы всего содержимого
             создаваемого фигурой во время рендеринга в координатном пространстве слайда.

Эти границы могут отличаться от модели границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отображаемое содержимое выходит за пределы начала слайда.

Визуальные границы учитывают связанные с рендерингом аспекты, такие как
             трансформации (например, вращение), ширина и соединения линий,
             верстка текста и переполнение, геометрия SmartArt и другие эффекты
             оформления, влияющие на конечный визуальный вид фигуры.

Возвращаемые границы не обрезаются до прямоугольника слайда.

### См. также
* класс [`SectionZoomFrame`](/slides/python-net/ru/aspose.slides/sectionzoomframe)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)