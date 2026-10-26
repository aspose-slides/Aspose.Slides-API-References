---
title: get_Description()
second_title: مرجع API Aspose.Slides برای C++
description: متن توصیف شیء Summary Zoom Section را بر می‌گرداند.
type: docs
weight: 27
url: /fa/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() متد


متن توضیح شیء Summary Zoom [Section](../../section/) را بر می‌گرداند.

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
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
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)