---
title: get_visual_bounds method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого.

### Возвращаемое значение

Объект **aspose.slides.RectangleF**, представляющий визуальные границы фигуры в координатах слайда.

```python
def get_visual_bounds(self):
    ...
```

### Примечания

Возвращаемый прямоугольник представляет собой осесимметричные границы всего содержимого,
             создаваемого фигурой во время отрисовки в координатах слайда.
             
             Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала слайда.
             
             Визуальные границы учитывают связанные с отрисовкой аспекты, такие как
             трансформации (например, вращение), ширина и соединения штрихов,
             расположение текста и переполнение, геометрию SmartArt и другие эффекты разметки,
             которые влияют на окончательный визуальный вид фигуры.
             
             Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`SmartArt`](/slides/python-net/ru/aspose.slides.smartart/smartart)
* модуль [`aspose.slides.smartart`](/slides/python-net/ru/aspose.slides.smartart)
* библиотека [`Aspose.Slides`](/slides/python-net)