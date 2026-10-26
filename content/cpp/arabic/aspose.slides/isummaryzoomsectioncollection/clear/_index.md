---
title: Clear()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يزيل جميع كائنات SummaryZoomSection من المجموعة.
type: docs
weight: 66
url: /ar/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() طريقة

يزيل جميع كائنات [SummaryZoomSection](../../summaryzoomsection/) من المجموعة.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## ملاحظات

يوضح المثال الحصول على عنصر Summary Zoom [Section](../../section/) بواسطة الفهرس:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## انظر أيضًا

* فئة [ISummaryZoomSectionCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)