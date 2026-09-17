---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
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

Возвращаемый прямоугольник представляет осно́вные (выравненные по осям) границы всего содержимого, генерируемого фигурой при рендеринге в координатном пространстве слайда.
            
Эти границы могут отличаться от модельных границ фигуры ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height)) и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала слайда.
            
Визуальные границы учитывают связанные с рендерингом аспекты, такие как трансформации (например, поворот), ширина и соединения обводки, расположение текста и переполнение, геометрию SmartArt и другие эффекты компоновки, влияющие на окончательный внешний вид фигуры.
            
Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`Chart`](/slides/python-net/ru/aspose.slides.charts/chart)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)