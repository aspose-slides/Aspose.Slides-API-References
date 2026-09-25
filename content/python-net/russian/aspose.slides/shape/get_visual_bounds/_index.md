---
title: get_visual_bounds method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого.

### Возвращаемое значение

Объект [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef), представляющий визуальные границы фигуры
             в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Примечания

Возвращаемый прямоугольник представляет собой осево-ориентированные границы всего содержимого
             создаваемого фигурой во время отрисовки в системе координат слайда.
            
             Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала слайда.
            
             Визуальные границы учитывают аспекты, связанные с отрисовкой, такие как
             трансформации (например, вращение), ширина и соединения линий,
             макет текста и переполнение, геометрия SmartArt и другие эффекты компоновки,
             влияющие на окончательный визуальный вид фигуры.
            
             Возвращаемые границы не обрезаются по прямоугольнику слайда.



### См. также
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)