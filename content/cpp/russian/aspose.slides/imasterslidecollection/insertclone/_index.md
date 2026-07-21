---
title: InsertClone()
second_title: Aspose.Slides для C++ справочник API
description: Вставляет копию указанного мастер-слайда в указанную позицию коллекции. Связанные слайды-шаблоны также будут скопированы.
type: docs
weight: 66
url: /ru/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) method

Вставляет копию указанного мастер-слайда в указанную позицию коллекции. Связанные слайд-шаблоны также будут скопированы.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) для клонирования. |

### Возвращаемое значение

Вставленный мастер-слайд.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMasterSlide](../../imasterslide/)
* Класс [IMasterSlideCollection](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)