---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого.

### Возвращаемое значение

A **aspose.slides.RectangleF**, представляющий визуальные границы фигуры в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Примечания

Возвращаемый прямоугольник представляет осево-выравненные границы всего содержимого,
             генерируемого фигурой во время отрисовки в пространстве координат слайда.

Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала слайда.

Визуальные границы учитывают связанные с отрисовкой аспекты, такие как
             преобразования (например, вращение), ширина и соединения штрихов,
             раскладка текста и переполнение, геометрия SmartArt и другие эффекты раскладки,
             влияющие на окончательный отрисованный вид фигуры.

Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`Ink`](/slides/python-net/ru/aspose.slides.ink/ink)
* модуль [`aspose.slides.ink`](/slides/python-net/ru/aspose.slides.ink)
* библиотека [`Aspose.Slides`](/slides/python-net)