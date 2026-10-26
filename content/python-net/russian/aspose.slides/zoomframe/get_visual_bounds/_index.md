---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/zoomframe/get_visual_bounds/
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

Возвращаемый прямоугольник представляет собой выровненные по осям границы всего содержимого
             созданные фигурой во время отрисовки в системе координат слайда.

             
             Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое расширяется
             за пределы начала слайда.
             
             Визуальные границы учитывают связанные с отрисовкой аспекты, такие как
             преобразования (например, вращение), ширина линии и соединения,
             раскладка текста и переполнение, геометрия SmartArt и другие эффекты раскладки
             влияющие на окончательный отрисованный вид фигуры.
             
             Возвращаемые границы не обрезаются по прямоугольнику слайда.



### Смотрите также
* класс [`ZoomFrame`](/slides/python-net/ru/aspose.slides/zoomframe)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)