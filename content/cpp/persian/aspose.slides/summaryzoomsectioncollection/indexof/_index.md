---
title: IndexOf()
second_title: Aspose.Slides برای C++ مرجع API
description: یک اندیس از شیء SummaryZoomSection مشخص شده را برمی‌گرداند.
type: docs
weight: 66
url: /fa/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) متد

یک اندیس از شیء [SummaryZoomSection](../../summaryzoomsection/) مشخص شده را برمی‌گرداند.

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) شیء برای یافتن [ISummaryZoomSection](../../isummaryzoomsection/). |

### مقدار بازگشتی

اندیس یک شیء [SummaryZoomSection](../../summaryzoomsection/) یا -1 در صورتی که شیء [SummaryZoomSection](../../summaryzoomsection/) از این مجموعه نباشد.

## ملاحظات

این مثال نشان می‌دهد که چگونه عنصر [Section](../../section/) Summary Zoom را بر اساس اندیس دریافت می‌کنید:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISummaryZoomSection](../../isummaryzoomsection/)
* کلاس [SummaryZoomSectionCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)