---
title: equals method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/notesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Определяет, равны ли два экземпляра IBaseSlide.  
Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого.  
Два слайда считаются равными, если все формы, стили, тексты, анимация и прочие настройки и т. д. одинаковы. Сравнение не учитывает значения уникальных идентификаторов, например SlideId, и динамического содержимого, например текущего значения даты в Заполнителе даты.

### Возвращаемое значение

**true**  если указанный IBaseSlide равен текущему IBaseSlide; иначе, **false** .

```python
def equals(self, slide):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide) | IBaseSlide для сравнения с текущим IBaseSlide. |

### Смотрите также
* класс [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide)
* класс [`NotesSlide`](/slides/python-net/ru/aspose.slides/notesslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)