---
title: equals method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/slide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Определяет, равны ли два экземпляра IBaseSlide.
            Возвращаемое значение рассчитывается на основе структуры слайда и статического контента.
            Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие настройки и т. д. равны. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамический контент, например текущее значение даты в заполнителе даты.

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
* класс [`Slide`](/slides/python-net/ru/aspose.slides/slide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)