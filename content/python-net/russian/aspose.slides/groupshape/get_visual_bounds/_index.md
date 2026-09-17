---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, рассчитанные на основе её отрисованного содержимого.

### Возвращаемое значение

Объект **aspose.slides.RectangleF**, представляющий визуальные границы фигуры в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Замечания

Возвращаемый прямоугольник представляет собой выравненные по осям границы всего содержимого, создаваемого фигурой во время рендеринга в координатном пространстве слайда.

Эти границы могут отличаться от модельных границ фигуры ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height)) и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала слайда.

Визуальные границы учитывают связанные с рендерингом аспекты, такие как трансформации (например, вращение), ширина и соединения штриха, разметка и переполнение текста, геометрия SmartArt и другие эффекты разметки, влияющие на окончательный визуальный вид фигуры.

Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`GroupShape`](/slides/python-net/ru/aspose.slides/groupshape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)