---
title: AddSummaryZoomSection()
second_title: Aspose.Slides для C++ API Reference
description: Создает новый объект Summary Zoom Section и добавляет его в коллекцию
type: docs
weight: 53
url: /ru/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) метод

Создает новый объект Summary Zoom [Section](../../section/) и добавляет его в коллекцию

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) для нового элемента Summary Zoom [Section](../../section/) [ISection](../../isection/) |

### Возвращаемое значение

Добавлен [ISummaryZoomFrame](../../isummaryzoomframe/) элемент

## Примечания

Если элемент для этого раздела уже существует в коллекции, возвращается существующий элемент.

Пример демонстрирует получение элемента Summary Zoom [Section](../../section/) по индексу:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomSection](../../isummaryzoomsection/)
* Класс [ISection](../../isection/)
* Класс [SummaryZoomSectionCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)