---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/videoframe/get_visual_bounds/
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

Возвращаемый прямоугольник представляет собой выровненные по осям границы всего содержимого,
             создаваемого фигурой во время отрисовки в координатном пространстве слайда.
            
             Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала слайда.
            
             В визуальные границы учитываются связанные с отрисовкой аспекты, такие как трансформации (например, вращение), ширина и соединения линий,
             макет текста и переполнение, геометрия SmartArt и другие эффекты макета,
             влияющие на окончательный визуальный вид фигуры.
            
             Возвращаемые границы не обрезаются прямоугольником слайда.



### См. также
* класс [`VideoFrame`](/slides/python-net/ru/aspose.slides/videoframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)