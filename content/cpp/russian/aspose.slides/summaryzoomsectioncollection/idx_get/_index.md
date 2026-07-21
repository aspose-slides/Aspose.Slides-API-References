---
title: idx_get()
second_title: Справочник API Aspose.Slides для C++
description: Получает элемент по указанному индексу. Только для чтения ISummaryZoomSection.
type: docs
weight: 40
url: /ru/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) метод


Получает элемент по указанному индексу. Только для чтения [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## Примечания


Пример демонстрирует получение элемента Summary Zoom [Section](../../section/) по индексу: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomSection](../../isummaryzoomsection/)
* Класс [SummaryZoomSectionCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)