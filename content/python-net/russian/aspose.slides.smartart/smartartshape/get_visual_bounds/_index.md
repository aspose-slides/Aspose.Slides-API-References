---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого.

### Возвращаемое значение
Объект [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef), представляющий визуальные границы фигуры в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Примечания
Возвращаемый прямоугольник представляет осью-выравненные границы всего содержимого
             производимого фигурой во время рендеринга в координатном пространстве слайда.

Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое расширяется
             за пределы начала слайда.

Визуальные границы учитывают связанные с рендерингом аспекты, такие как
             преобразования (например, вращение), ширина штриха и соединения,
             раскладка текста и переполнение, геометрия SmartArt и другие эффекты макета
             которые влияют на окончательный отрисованный вид фигуры.

Возвращаемые границы не обрезаются до прямоугольника слайда.

### См. также
* класс [`SmartArtShape`](/slides/python-net/ru/aspose.slides.smartart/smartartshape)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides.smartart`](/slides/python-net/ru/aspose.slides.smartart)
* библиотека [`Aspose.Slides`](/slides/python-net)