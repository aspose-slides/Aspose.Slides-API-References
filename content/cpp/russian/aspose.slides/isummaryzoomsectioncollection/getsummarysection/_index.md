---
title: GetSummarySection()
second_title: Aspose.Slides для C++ Справочник API
description: Возвращает элемент Summary Zoom Section для указанного раздела.
type: docs
weight: 27
url: /ru/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) метод

Возвращает элемент Summary Zoom [Section](../../section/) для указанного раздела.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) для поиска [ISection](../../isection/) |

### Возвращаемое значение

[ISummaryZoomSection](../../isummaryzoomsection/) или null, если коллекция не содержит элемент для раздела.

## Примечания

Пример демонстрирует получение элемента Summary Zoom [Section](../../section/) по индексу:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomSection](../../isummaryzoomsection/)
* Класс [ISection](../../isection/)
* Класс [ISummaryZoomSectionCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)