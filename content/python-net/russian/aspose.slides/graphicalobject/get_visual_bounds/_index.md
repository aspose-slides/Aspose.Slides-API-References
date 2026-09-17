---
title: get_visual_bounds method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, рассчитанные по её отрисованному содержимому.

### Возвращаемое значение

Объект **aspose.slides.RectangleF**, представляющий визуальные границы фигуры
             в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Замечания

Возвращаемый прямоугольник представляет собой ориентированные по осям границы всего содержимого
             созданные фигурой во время отрисовки в координатном пространстве слайда.

Эти границы могут отличаться от модельных границ фигуры
([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала слайда.

Визуальные границы учитывают связанные с отрисовкой аспекты, такие как
трансформации (например, вращение), ширина и соединения штрихов,
             верстка текста и переполнение, геометрия SmartArt и другие эффекты компоновки
             влияющие на окончательный отрисованный вид фигуры.

Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)