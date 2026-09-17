---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description:
type: docs
url: /ru/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные на основе её отрисованного содержимого.

### Возвращаемое значение

Объект **aspose.slides.RectangleF**, представляющий визуальные границы фигуры
             в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Примечание

Возвращаемый прямоугольник представляет собой осночно-выравненные границы всего содержимого,
             созданного фигурой во время отрисовки в координатном пространстве слайда.
            
Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала координат слайда.
            
В визуальные границы учитываются связанные с отрисовкой аспекты, такие как
             трансформации (например, вращение), ширина и соединения линий,
             компоновка и переполнение текста, геометрия SmartArt и другие эффекты компоновки,
             влияющие на окончательный отрисованный вид фигуры.
            
Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`AudioFrame`](/slides/python-net/ru/aspose.slides/audioframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)