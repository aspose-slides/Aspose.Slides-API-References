---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/sectionzoomframe/get_visual_bounds/
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

Возвращаемый прямоугольник представляет границы, выровненные по осям, всего содержимого,
             генерируемого фигурой во время рендеринга в координатном пространстве слайда.
            
             Эти границы могут отличаться от модели границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала слайда.
            
             Визуальные границы учитывают связанные с рендерингом аспекты, такие как
             трансформации (например, вращение), ширина и соединения обводки,
             компоновка текста и переполнение, геометрию SmartArt и другие эффекты компоновки,
             влияющие на окончательный отрисованный вид фигуры.
            
             Возвращаемые границы не обрезаются до прямоугольника слайда.



### См. также
* класс [`SectionZoomFrame`](/slides/python-net/ru/aspose.slides/sectionzoomframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)