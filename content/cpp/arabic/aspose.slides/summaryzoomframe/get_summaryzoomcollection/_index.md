---
title: get_SummaryZoomCollection()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على ISummaryZoomSectionCollection لكائن Summary Zoom Frame.
type: docs
weight: 14
url: /ar/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() طريقة

يحصل على [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) لكائن Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## ملاحظات

يوضح المثال كيفية الحصول على عنصر Summary Zoom [Section](../../section/) حسب الفهرس:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* فئة [SummaryZoomFrame](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)