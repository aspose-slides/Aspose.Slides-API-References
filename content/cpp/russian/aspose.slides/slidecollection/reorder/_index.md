---
title: Reorder()
second_title: Справочник API Aspose.Slides для C++
description: Перемещает слайд из коллекции в указанную позицию.
type: docs
weight: 157
url: /ru/aspose.slides/slidecollection/reorder/
---
## SlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) метод

Перемещает слайд из коллекции в указанную позицию.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Целевой индекс. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для перемещения. |

## SlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) метод

Перемещает слайды из коллекции в указанную позицию. [Slides](../../) будет размещён начиная с индекса в порядке их появления в списке.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Целевой индекс. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) для перемещения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ISlide](../../islide/)
* Класс [SlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)