---
title: get_Title()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع عنوان النص لكائن Summary Zoom Section.
type: docs
weight: 1
url: /ar/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() طريقة


يرجع عنوان النص لكائن Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Title()=0
```

## ملاحظات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [ISummaryZoomSection](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)