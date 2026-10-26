---
title: idx_get()
second_title: Aspose.Slides مرجع API لـ C++
description: يحصل على العنصر في الفهرس المحدد. للقراءة فقط ISummaryZoomSection.
type: docs
weight: 40
url: /ar/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) طريقة


يحصل على العنصر في الفهرس المحدد. للقراءة فقط [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## ملاحظات


يوضح المثال الحصول على عنصر Summary Zoom [Section](../../section/) حسب الفهرس: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISummaryZoomSection](../../isummaryzoomsection/)
* فئة [SummaryZoomSectionCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)