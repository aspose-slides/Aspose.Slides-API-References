---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides для C++ справочник API
description: Получает ISummaryZoomSectionCollection для объекта Summary Zoom Frame.
type: docs
weight: 14
url: /ru/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() метод

Получает [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) для объекта Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Примечания

Пример демонстрирует получение элемента Summary Zoom [Section](../../section/) по индексу:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Класс [SummaryZoomFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)