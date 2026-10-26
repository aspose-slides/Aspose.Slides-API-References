---
title: get_Title()
second_title: Aspose.Slides برای مرجع API C++
description: عنوان متنی شیء Summary Zoom Section را برمی‌گرداند.
type: docs
weight: 1
url: /fa/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() متد


عنوان متنی شیء Summary Zoom [Section](../../section/) را برمی‌گرداند.

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

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [ISummaryZoomSection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)