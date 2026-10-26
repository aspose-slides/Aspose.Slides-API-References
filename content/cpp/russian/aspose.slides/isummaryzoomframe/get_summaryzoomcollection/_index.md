---
title: get_SummaryZoomCollection()
second_title: Справочник API Aspose.Slides для C++
description: Получает ISummaryZoomSectionCollection для объекта Summary Zoom Frame.
type: docs
weight: 14
url: /ru/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() метод


Получает [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) для объекта Summary Zoom Frame.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
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
* Класс [ISummaryZoomFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)