---
title: get_visual_bounds method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого.

### Возвращаемое значение

Объект [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef), представляющий визуальные границы фигуры в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Примечание

Возвращаемый прямоугольник представляет осно-ориентированные границы всего содержимого,
             созданного фигурой при отрисовке в пространстве координат слайда.
            
             Эти границы могут отличаться от модельных границ фигуры
             ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height))
             и могут содержать отрицательные координаты, если отрисованное содержимое выходит
             за пределы начала координат слайда.
            
             Визуальные границы учитывают связанные с рендерингом аспекты, такие как
             преобразования (например, вращение), ширина и соединения линий,
             компоновка и переполнение текста, геометрию SmartArt и другие эффекты компоновки,
             влияющие на окончательный визуальный вид фигуры.
            
             Возвращаемые границы не обрезаются до прямоугольника слайда.



### Смотрите также
* класс [`InkActions`](/slides/python-net/ru/aspose.slides.ink/inkactions)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides.ink`](/slides/python-net/ru/aspose.slides.ink)
* библиотека [`Aspose.Slides`](/slides/python-net)