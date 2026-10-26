---
title: set_Title()
second_title: Aspose.Slides لـ C++ مرجع API
description: يعيد عنوان النص لكائن Summary Zoom Section.
type: docs
weight: 14
url: /ar/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) طريقة

يُعيد عنوان النص لكائن Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
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
* فئة [SummaryZoomSection](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)