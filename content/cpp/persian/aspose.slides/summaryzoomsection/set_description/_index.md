---
title: set_Description()
second_title: Aspose.Slides برای C++ مرجع API
description: توضیح متنی شیء Summary Zoom Section را برمی‌گرداند.
type: docs
weight: 40
url: /fa/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) متد

متن توصیفی شیء Summary Zoom [Section](../../section/) را برمی‌گرداند.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
```

## توضیحات

مثال:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [SummaryZoomSection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)