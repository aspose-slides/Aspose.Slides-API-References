---
title: equals method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/masternotesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Определяет, равны ли два экземпляра IBaseSlide.
            Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого.
            Два слайда считаются равными, если все формы, стили, тексты, анимация и другие настройки и т.д. равны. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамическое содержимое, например текущее значение даты в заполнителе даты.

### Возвращаемое значение

**true**  если указанный IBaseSlide равен текущему IBaseSlide; 
            иначе **false** .



```python
def equals(self, slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide) | IBaseSlide для сравнения с текущим IBaseSlide. |



### См. также
* класс [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide)
* класс [`MasterNotesSlide`](/slides/python-net/ru/aspose.slides/masternotesslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)