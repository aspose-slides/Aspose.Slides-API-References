---
title: IndexOf()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает индекс указанного объекта SummaryZoomSection.
type: docs
weight: 66
url: /ru/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) метод

Возвращает индекс указанного объекта [SummaryZoomSection](../../summaryzoomsection/).

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) объект для поиска [ISummaryZoomSection](../../isummaryzoomsection/). |

### Возвращаемое значение

Индекс объекта [SummaryZoomSection](../../summaryzoomsection/) или -1, если объект [SummaryZoomSection](../../summaryzoomsection/) не из этой коллекции.

## Примечания

В примере демонстрируется получение элемента Summary Zoom [Section](../../section/) по индексу:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomSection](../../isummaryzoomsection/)
* Класс [SummaryZoomSectionCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)