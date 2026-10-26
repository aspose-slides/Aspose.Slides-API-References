---
title: equals method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/masterslide/equals/
weight: 30
---
## equals(self, slide) {#ibaseslide}
Определяет, равны ли два экземпляра IBaseSlide.  
Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого.  
Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие настройки и т. д. одинаковы. При сравнении не учитываются уникальные значения идентификаторов, например SlideId, и динамическое содержимое, например текущая дата в заполнителе даты.

### Возвращаемое значение

**true**  если указанный IBaseSlide равен текущему IBaseSlide;  
в противном случае **false** .

```python
def equals(self, slide):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide) | IBaseSlide, с которым сравнивается текущий IBaseSlide. |

### Смотрите также
* класс [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide)
* класс [`MasterSlide`](/slides/python-net/ru/aspose.slides/masterslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)