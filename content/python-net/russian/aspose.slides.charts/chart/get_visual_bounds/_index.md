---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, рассчитанные из её отрисованного содержимого.

### Возвращаемое значение

Объект [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef), представляющий визуальные границы фигуры в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Примечания

Возвращаемый прямоугольник представляет собой осно-ориентированные границы всего содержимого,
создаваемого фигурой во время отрисовки, в системе координат слайда.

Эти границы могут отличаться от модельных границ фигуры
([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
и могут содержать отрицательные координаты, если отрисованное содержимое выходит
за пределы начала слайда.

Визуальные границы учитывают связанные с отрисовкой аспекты, такие как
трансформации (например, вращение), ширина и соединения линий,
размещение текста и переполнение, геометрию SmartArt и другие эффекты компоновки,
влияющие на окончательный внешний вид фигуры.

Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`Chart`](/slides/python-net/ru/aspose.slides.charts/chart)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)