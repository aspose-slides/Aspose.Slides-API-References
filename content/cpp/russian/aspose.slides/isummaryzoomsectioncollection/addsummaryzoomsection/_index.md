---
title: AddSummaryZoomSection()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый объект Summary Zoom Section и добавляет его в коллекцию
type: docs
weight: 14
url: /ru/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) метод

Создаёт новый объект Summary Zoom [Section](../../section/) и добавляет его в коллекцию

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) для нового элемента Summary Zoom [Section](../../section/) [ISection](../../isection/) |

### Возвращаемое значение

Добавлен элемент [ISummaryZoomFrame](../../isummaryzoomframe/)

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

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomSection](../../isummaryzoomsection/)
* Класс [ISection](../../isection/)
* Класс [ISummaryZoomSectionCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)