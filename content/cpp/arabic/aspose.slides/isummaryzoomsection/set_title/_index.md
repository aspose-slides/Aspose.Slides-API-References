---
title: set_Title()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد عنوان النص لكائن Summary Zoom Section.
type: docs
weight: 14
url: /ar/aspose.slides/isummaryzoomsection/set_title/
---
## ISummaryZoomSection::set_Title(System::String) طريقة

يُرجِع عنوان النص لكائن Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Title(System::String value)=0
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
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)