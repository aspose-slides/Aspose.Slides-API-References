---
title: get_visual_bounds method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Получает визуальные границы фигуры, вычисленные на основе её отрендеренного содержимого.

### Возвращаемое значение

Объект **aspose.slides.RectangleF**, представляющий визуальные границы фигуры в координатах слайда.



```python
def get_visual_bounds(self):
    ...
```


### Примечания

Возвращаемый прямоугольник представляет собой осево-выравненные границы всего содержимого, создаваемого фигурой во время рендеринга в координатном пространстве слайда.

Эти границы могут отличаться от границ модели фигуры ([`Shape.x`](/slides/python-net/ru/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ru/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ru/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ru/aspose.slides/shape/height)) и могут содержать отрицательные координаты, если отрендеренное содержимое выходит за пределы начала слайда.

Визуальные границы учитывают связанные с рендерингом аспекты, такие как трансформации (например, вращение), ширина и соединения штриха, верстка и переполнение текста, геометрия SmartArt и другие эффекты компоновки, влияющие на окончательный отрисованный вид фигуры.

Возвращённые границы не обрезаются до прямоугольника слайда.



### Смотрите также
* класс [`InkActions`](/slides/python-net/ru/aspose.slides.ink/inkactions)
* модуль [`aspose.slides.ink`](/slides/python-net/ru/aspose.slides.ink)
* библиотека [`Aspose.Slides`](/slides/python-net)