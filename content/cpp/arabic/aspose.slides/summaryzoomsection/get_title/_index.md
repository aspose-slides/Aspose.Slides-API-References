---
title: get_Title()
second_title: Aspose.Slides لـ C++ مرجع API
description: يرجع عنوان النص لكائن Summary Zoom Section.
type: docs
weight: 1
url: /ar/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() طريقة


Returns the text title of the Summary Zoom [Section](../../section/) object.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
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
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)