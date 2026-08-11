---
title: idx_get()
second_title: مرجع API Aspose.Slides برای C++
description: عنصر را در اندیس مشخص دریافت می‌کند. فقط خواندنی ISummaryZoomSection.
type: docs
weight: 1
url: /fa/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) متد


عنصر را در ایندکس مشخص دریافت می‌کند. فقط خواندنی [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## توضیحات


مثال نحوه دریافت عنصر Summary Zoom [Section](../../section/) با استفاده از ایندکس را نشان می‌دهد: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISummaryZoomSection](../../isummaryzoomsection/)
* کلاس [ISummaryZoomSectionCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)