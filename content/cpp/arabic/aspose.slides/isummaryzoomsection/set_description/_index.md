---
title: set_Description()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد الوصف النصي لكائن Summary Zoom Section.
type: docs
weight: 40
url: /ar/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) طريقة


يعيد الوصف النصي لكائن Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
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

* الفئة [String](../../../system/string/)
* الفئة [ISummaryZoomSection](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)