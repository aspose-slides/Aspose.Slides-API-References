---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные на основе её отрисованного содержимого.

### Возвращаемое значение

Объект [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef), представляющий визуальные границы фигуры
             в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Примечания

Возвращаемый прямоугольник представляет собой ориентированные по осям границы всего содержимого, созданного фигурой во время отрисовки в координатном пространстве слайда.
            
Эти границы могут отличаться от модельных границ фигуры ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height)) и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала слайда.
            
В визуальные границы учитываются связанные с отрисовкой аспекты, такие как преобразования (например, поворот), ширина и соединения линий, компоновка и переполнение текста, геометрия SmartArt и другие эффекты компоновки, влияющие на окончательный визуальный вид фигуры.
            
Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`ZoomObject`](/slides/python-net/ru/aspose.slides/zoomobject)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)