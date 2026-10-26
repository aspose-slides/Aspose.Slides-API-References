---
title: set_Title()
second_title: Aspose.Slides برای C++ مرجع API
description: عنوان متنی شیء Summary Zoom Section را برمی‌گرداند.
type: docs
weight: 14
url: /fa/aspose.slides/isummaryzoomsection/set_title/
---
## ISummaryZoomSection::set_Title(System::String) method


عنوان متنی شیء Summary Zoom [Section](../../section/) را برمی‌گرداند.

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Title(System::String value)=0
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
* کلاس [ISummaryZoomSection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)