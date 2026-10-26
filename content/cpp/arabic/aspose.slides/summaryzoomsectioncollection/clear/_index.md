---
title: Clear()
second_title: Aspose.Slides لـ C++ مرجع API
description: يزيل جميع كائنات SummaryZoomSection من المجموعة.
type: docs
weight: 105
url: /ar/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() طريقة

يزيل جميع الكائنات [SummaryZoomSection](../../summaryzoomsection/) من المجموعة.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
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

* فئة [SummaryZoomSectionCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)