---
title: equals method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/layoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Определяет, являются ли два экземпляра IBaseSlide одинаковыми.
            Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого.
            Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие параметры и т. д. одинаковы. Сравнение не учитывает уникальные значения идентификаторов, например SlideId, и динамическое содержимое, например текущее значение даты в Date Placeholder.

### Возвращаемое значение

**true**  если указанный IBaseSlide равен текущему IBaseSlide; 
            иначе, **false** .

```python
def equals(self, slide):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide) | IBaseSlide для сравнения с текущим IBaseSlide. |

### См. также
* класс [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide)
* класс [`LayoutSlide`](/slides/python-net/ru/aspose.slides/layoutslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)