---
title: set_Description()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يرجع الوصف النصي لكائن Summary Zoom Section.
type: docs
weight: 40
url: /ar/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) طريقة

يرجع الوصف النصي لكائن Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
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
* فئة [SummaryZoomSection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)