---
title: idx_get()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a megadott indexen lévő elemet. Csak olvasható ISummaryZoomSection.
type: docs
weight: 40
url: /hu/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) metódus

Lekéri a megadott indexen lévő elemet. Csak olvasható [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## Megjegyzések

A példa bemutatja a Summary Zoom [Section](../../section/) elem index szerinti lekérését:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ISummaryZoomSection](../../isummaryzoomsection/)
* Osztály [SummaryZoomSectionCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)