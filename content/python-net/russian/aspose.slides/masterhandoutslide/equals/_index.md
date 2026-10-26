---
title: equals method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Определяет, равны ли два экземпляра IBaseSlide.
            Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого.
            Слайды считаются равными, если все формы, стили, тексты, анимация и другие настройки и т.д. одинаковы. При сравнении не учитываются значения уникальных идентификаторов, например SlideId, и динамическое содержимое, например текущая дата в заполнителе даты.

### Возвращаемое значение

**true**  если указанный IBaseSlide равен текущему IBaseSlide; 
            в противном случае **false** .



```python
def equals(self, slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide) | IBaseSlide для сравнения с текущим IBaseSlide. |



### См. также
* класс [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide)
* класс [`MasterHandoutSlide`](/slides/python-net/ru/aspose.slides/masterhandoutslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)