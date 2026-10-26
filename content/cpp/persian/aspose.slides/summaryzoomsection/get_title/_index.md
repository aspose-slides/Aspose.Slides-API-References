---
title: get_Title()
second_title: مرجع API Aspose.Slides برای C++
description: عنوان متنی شیء Summary Zoom Section را برمی‌گرداند.
type: docs
weight: 1
url: /fa/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() متد


عنوان متنی شیء Summary Zoom [Section](../../section/) را برمی‌گرداند.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
```

## توضیحات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [SummaryZoomSection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)