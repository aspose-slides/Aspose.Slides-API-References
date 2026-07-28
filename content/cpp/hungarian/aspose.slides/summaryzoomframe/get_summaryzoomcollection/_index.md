---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides C++ API-referencia
description: Lekéri az ISummaryZoomSectionCollection-t a Summary Zoom Frame objektumhoz.
type: docs
weight: 14
url: /hu/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() metódus

Lekéri [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) a Summary Zoom Frame objektumhoz.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Megjegyzések

A példa bemutatja a Summary Zoom [Section](../../section/) elem index szerinti lekérését:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Osztály [SummaryZoomFrame](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)