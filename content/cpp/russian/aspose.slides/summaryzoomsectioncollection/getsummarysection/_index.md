---
title: GetSummarySection()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает элемент Summary Zoom Section для указанного раздела.
type: docs
weight: 92
url: /ru/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) метод

Возвращает Summary Zoom [Section](../../section/) элемент для указанного раздела.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) для поиска [ISection](../../isection/) |

### Возвращаемое значение

[ISummaryZoomSection](../../isummaryzoomsection/) или null, если коллекция не содержит элемент для раздела.

## Примечания

Пример демонстрирует получение Summary Zoom [Section](../../section/) элемента по индексу:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomSection](../../isummaryzoomsection/)
* Класс [ISection](../../isection/)
* Класс [SummaryZoomSectionCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)