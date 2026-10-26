---
title: get_Description()
second_title: Aspose.Slides برای C++ راهنمای API
description: توضیح متنی شی Summary Zoom Section را بر می‌گرداند.
type: docs
weight: 27
url: /fa/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() متد

توضیح متنی شی [Section](../../section/) خلاصهٔ زوم را بر می‌گرداند.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
```

## توضیح

مثال:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [SummaryZoomSection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)