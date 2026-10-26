---
title: IndexOf()
second_title: Aspose.Slides для C++ справочника API
description: Возвращает индекс указанного объекта SummaryZoomSection.
type: docs
weight: 53
url: /ru/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) метод

Возвращает индекс указанного [SummaryZoomSection](../../summaryzoomsection/) объекта.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) объект для поиска [ISummaryZoomSection](../../isummaryzoomsection/). |

### Возвращаемое значение

Индекс [SummaryZoomSection](../../summaryzoomsection/) объекта или -1, если [SummaryZoomSection](../../summaryzoomsection/) объект не из этой коллекции.

## Примечания

Пример демонстрирует получение элемента Summary Zoom [Section](../../section/) по индексу:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)