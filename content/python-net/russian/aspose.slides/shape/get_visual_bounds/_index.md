---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET API
description: 
type: docs
url: /ru/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрендеренного содержимого.

### Возврат

Объект **aspose.slides.RectangleF**, представляющий визуальные границы фигуры в координатах слайда



```python
def get_visual_bounds(self):
    ...
```


### Примечания

Возвращаемый прямоугольник представляет собой осево-ориентированные границы всего содержимого,
                  созданного фигурой во время рендеринга в пространстве координат слайда.

                  Эти границы могут отличаться от модельных границ фигуры
                  ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
                  [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
                  и могут содержать отрицательные координаты, если отрендеренное содержимое выходит
                  за пределы начала слайда.

                  Визуальные границы учитывают связанные с рендерингом аспекты, такие как
                  преобразования (например, поворот), ширина и соединения обводки,
                  размещение текста и переполнение, геометрию SmartArt и другие эффекты компоновки,
                  влияющие на окончательный визуальный вид фигуры.

                  Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)