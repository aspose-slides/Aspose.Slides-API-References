---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого.

### Returns
Объект [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef), представляющий визуальные границы фигуры
             в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Remarks
Возвращаемый прямоугольник представляет осно-ориентированные границы всего содержимого,
             создаваемого фигурой при рендеринге в координатном пространстве слайда.
            
             Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала слайда.
            
             Визуальные границы учитывают связанные с отрисовкой аспекты, такие как
             преобразования (например, вращение), ширина и соединения линий,
             расположение текста и переполнение, геометрию SmartArt и другие эффекты компоновки,
             влияющие на окончательный внешний вид фигуры после рендеринга.
            
             Возвращаемые границы не отсекаются по прямоугольнику слайда.



### See Also
* класс [`OleObjectFrame`](/slides/python-net/ru/aspose.slides/oleobjectframe)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)