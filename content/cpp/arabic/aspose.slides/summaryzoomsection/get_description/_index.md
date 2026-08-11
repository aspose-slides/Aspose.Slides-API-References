---
title: get_Description()
second_title: Aspose.Slides لـ C++ مرجع API
description: يعيد الوصف النصي لكائن Summary Zoom Section.
type: docs
weight: 27
url: /ar/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() طريقة

يرجع الوصف النصي لكائن Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
```

## ملاحظات

مثال:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## أنظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [SummaryZoomSection](../)
* نطاق الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)