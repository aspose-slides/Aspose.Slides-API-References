---
title: get_visual_bounds method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/table/get_visual_bounds/
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


### Примечания

Возвращаемый прямоугольник представляет собой осночно-выравненные границы всего содержимого
             создаваемого фигурой во время отрисовки в пространстве координат слайда.
            
             Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала слайда.
            
             В визуальные границы учитываются связанные с отрисовкой аспекты, такие как
             преобразования (например, вращение), ширина и соединения обводки,
             разметка текста и переполнение, геометрия SmartArt и другие эффекты разметки,
             влияющие на окончательный отрисованный вид фигуры.
            
             Возвращаемые границы не обрезаются по прямоугольнику слайда.



### См. также
* класс [`Table`](/slides/python-net/ru/aspose.slides/table)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)