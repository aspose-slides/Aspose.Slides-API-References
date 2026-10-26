---
title: idx_get()
second_title: Aspose.Slides C++ API referencia
description: A megadott indexű elemet adja vissza. Csak olvasható ISummaryZoomSection.
type: docs
weight: 1
url: /hu/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) metódus

A megadott indexnél lévő elemet adja vissza. Csak olvasható [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
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
* Osztály [ISummaryZoomSectionCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)