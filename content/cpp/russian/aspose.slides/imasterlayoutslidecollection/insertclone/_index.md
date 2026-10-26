---
title: InsertClone()
second_title: Aspose.Slides для C++ – справка по API
description: Вставляет копию указанного слайда-макета в заданную позицию коллекции.
type: docs
weight: 14
url: /ru/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) метод


Вставляет копию указанного слайда-макета в заданную позицию коллекции.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) для клонирования. |

### Возвращаемое значение

Вставленный слайд.
## Примечания



Новый макет будет связан с родительским мастером-слайдом для этой коллекции макетов слайдов. Таким образом, это аналог копирования/вставки с параметром «Use Destination Theme» в PowerPoint. 

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [IMasterLayoutSlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)