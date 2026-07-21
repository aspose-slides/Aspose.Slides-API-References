---
title: InsertClone()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет копию указанного слайда макета в указанную позицию коллекции.
type: docs
weight: 14
url: /ru/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) метод

Вставляет копию указанного слайда макета в указанную позицию коллекции.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) для клонирования. |

### Возвращаемое значение

Вставленный слайд.

## Замечания

Новый макет будет связан с родительским мастер-слайдом для этой коллекции слайдов макета. Таким образом, это аналог операции копировать/вставить с опцией \"Use Destination Theme\" в PowerPoint.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [MasterLayoutSlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)