---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого.

### Возвращаемое значение

Объект **aspose.slides.RectangleF**, представляющий визуальные границы фигуры
             в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Примечания

Возвращаемый прямоугольник представляет собой выровненные по осям границы всего содержимого
             создаваемого фигурой во время отрисовки в пространстве координат слайда.
            
Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала слайда.
            
Визуальные границы учитывают связанные с отрисовкой аспекты, такие как
             преобразования (например, вращение), ширина и соединения штрихов,
             расположение текста и переполнение, геометрия SmartArt и другие эффекты компоновки,
             влияющие на конечный визуальный вид фигуры.
            
Возвращаемые границы не обрезаются по прямоугольнику слайда.



### См. также
* класс [`SmartArtShape`](/slides/python-net/ru/aspose.slides.smartart/smartartshape)
* модуль [`aspose.slides.smartart`](/slides/python-net/ru/aspose.slides.smartart)
* библиотека [`Aspose.Slides`](/slides/python-net)