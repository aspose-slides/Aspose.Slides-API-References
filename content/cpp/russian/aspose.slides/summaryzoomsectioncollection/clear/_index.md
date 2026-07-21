---
title: Clear()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет все объекты SummaryZoomSection из коллекции.
type: docs
weight: 105
url: /ru/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() метод

Удаляет все [SummaryZoomSection](../../summaryzoomsection/) объекты из коллекции.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Примечания


Пример демонстрирует получение элемента Summary Zoom [Section](../../section/) по индексу: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## См. также

* Класс [SummaryZoomSectionCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)