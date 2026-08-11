---
title: idx_get()
second_title: Aspose.Slides برای مرجع API C++
description: عنصر را در شاخص مشخص‌شده دریافت می‌کند. فقط-خواندنی ISummaryZoomSection.
type: docs
weight: 40
url: /fa/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) متد

عنصری که در شاخص مشخص‌شده قرار دارد را بازمی‌گرداند. فقط-خواندنی [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## توضیحات

این مثال دریافت عنصر Summary Zoom [Section](../../section/) بر اساس شاخص را نشان می‌دهد:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISummaryZoomSection](../../isummaryzoomsection/)
* کلاس [SummaryZoomSectionCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)