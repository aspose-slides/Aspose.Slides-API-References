---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides C++ API hivatkozás
description: Lekéri az ISummaryZoomSectionCollection-t a Summary Zoom Frame objektumhoz.
type: docs
weight: 14
url: /hu/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() metódus


[ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) lekérhető a Summary Zoom Frame objektumhoz.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Megjegyzés


A példa bemutatja, hogyan lehet index alapján lekérni a Summary Zoom [Section](../../section/) elemet: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Osztály [ISummaryZoomFrame](../)
* Névtere [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)