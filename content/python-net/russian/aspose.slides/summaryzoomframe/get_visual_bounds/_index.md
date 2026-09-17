---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
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


### Замечания

Возвращаемый прямоугольник представляет осно-ориентированные границы всего содержимого
             создаваемого фигурой во время отрисовки в системе координат слайда.
            
Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала слайда.
            
Визуальные границы учитывают связанные с отрисовкой аспекты, такие как
             трансформации (например, вращение), ширина и соединения линий,
             компоновка текста и переполнение, геометрия SmartArt и другие эффекты компоновки,
             влияющие на окончательный отрисованный вид фигуры.
            
Возвращаемые границы не обрезаются по прямоугольнику слайда.



### См. также
* класс [`SummaryZoomFrame`](/slides/python-net/ru/aspose.slides/summaryzoomframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)