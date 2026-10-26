---
title: GetSummarySection()
second_title: Aspose.Slides برای C++ مرجع API
description: عنصر بخش Summary Zoom را برای بخش داده‌شده برمی‌گرداند.
type: docs
weight: 92
url: /fa/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) متد

عنصری از نوع Summary Zoom [Section](../../section/) را برای بخش داده شده برمی‌گرداند.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) برای پیدا کردن [ISection](../../isection/) |

## مقدار بازگشت

[ISummaryZoomSection](../../isummaryzoomsection/) یا null در صورتی که مجموعه عنصری برای بخش نداشته باشد.

## توضیحات

این مثال نحوه دریافت عنصر Summary Zoom [Section](../../section/) را بر اساس شاخص نشان می‌دهد:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISummaryZoomSection](../../isummaryzoomsection/)
* کلاس [ISection](../../isection/)
* کلاس [SummaryZoomSectionCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)