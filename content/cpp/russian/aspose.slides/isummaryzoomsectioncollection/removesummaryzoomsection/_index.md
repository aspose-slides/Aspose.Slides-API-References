---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides для C++ API справка
description: Удалить объект Summary Zoom Section из коллекции.
type: docs
weight: 40
url: /ru/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) метод

Удалить объект Summary Zoom [Section](../../section/) из коллекции.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) для которого элемент Summary Zoom [Section](../../section/) должен быть удалён [ISection](../../isection/). |
## Примечания

Пример демонстрирует получение элемента Summary Zoom [Section](../../section/) по индексу: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISection](../../isection/)
* Класс [ISummaryZoomSectionCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)