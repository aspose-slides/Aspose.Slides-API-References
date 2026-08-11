---
title: get_Description()
second_title: Aspose.Slides للغة C++ مرجع API
description: يعيد الوصف النصي لكائن Summary Zoom Section.
type: docs
weight: 27
url: /ar/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() طريقة

يعيد الوصف النصي لكائن Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
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

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [ISummaryZoomSection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)