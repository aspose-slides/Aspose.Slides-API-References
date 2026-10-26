---
title: get_SummaryZoomCollection()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على ISummaryZoomSectionCollection لكائن Summary Zoom Frame.
type: docs
weight: 14
url: /ar/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() طريقة

يحصل على [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) لكائن Summary Zoom Frame.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## ملاحظات

يوضح المثال الحصول على عنصر Summary Zoom [Section](../../section/) عبر الفهرس:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* الفئة [ISummaryZoomFrame](../)
* النطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)