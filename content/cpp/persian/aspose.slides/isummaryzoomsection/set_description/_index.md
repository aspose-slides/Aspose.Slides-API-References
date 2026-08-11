---
title: set_Description()
second_title: مرجع API Aspose.Slides برای C++
description: متن توصیفی شیء Summary Zoom Section را برمی‌گرداند.
type: docs
weight: 40
url: /fa/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) متد

متن توصیفی شیء Summary Zoom [Section](../../section/) را برمی‌گرداند.

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
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

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [ISummaryZoomSection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)