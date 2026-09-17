---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справка API
description: 
type: docs
url: /ru/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Возвращает визуальные границы фигуры, вычисленные на основе её отрисованного содержимого.

### Возвращаемое значение

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Замечания

Возвращаемый прямоугольник представляет собой осно-выравненные границы всего содержимого,
             создаваемого фигурой во время отрисовки в координатном пространстве слайда.

Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала слайда.

В визуальные границы учитываются связанные с отрисовкой аспекты, такие как
             преобразования (например, вращение), ширина и соединения линий,
             размещение текста и переполнение, геометрия SmartArt, а также другие эффекты
             компоновки, влияющие на окончательный вид фигуры.

Возвращаемые границы не обрезаются по прямоугольнику слайда.



### См. также
* класс [`OleObjectFrame`](/slides/python-net/ru/aspose.slides/oleobjectframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)