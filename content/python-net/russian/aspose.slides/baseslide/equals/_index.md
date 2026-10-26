---
title: equals method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/baseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Определяет, равны ли два экземпляра IBaseSlide.
            Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого.
            Два слайда считаются равными, если все формы, стили, тексты, анимация и прочие настройки и т. д. одинаковы. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамическое содержимое, например текущее значение даты в заполнителе Date Placeholder.

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
* класс [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)
* класс [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)