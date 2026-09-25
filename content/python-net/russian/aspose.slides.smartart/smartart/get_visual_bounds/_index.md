---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.smartart/smartart/get_visual_bounds/
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

Возвращаемый прямоугольник представляет осно́вно-ориентированные границы всего содержимого,
             создаваемого фигурой во время рендеринга в пространстве координат слайда.
            
             Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала координат слайда.
            
             Визуальные границы учитывают связанные с рендерингом аспекты, такие как трансформации (например, вращение),
             толщина контура и соединения, расположение текста и переполнение, геометрия SmartArt и другие эффекты компоновки,
             влияющие на окончательный визуальный вид фигуры.
            
             Возвращённые границы не обрезаются прямоугольником слайда.



### См. также
* класс [`SmartArt`](/slides/python-net/ru/aspose.slides.smartart/smartart)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides.smartart`](/slides/python-net/ru/aspose.slides.smartart)
* библиотека [`Aspose.Slides`](/slides/python-net)