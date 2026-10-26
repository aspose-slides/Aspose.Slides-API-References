---
title: GetSummarySection()
second_title: Aspose.Slides برای مرجع API C++
description: عنصر Summary Zoom Section را برای بخش داده شده برمی‌گرداند.
type: docs
weight: 27
url: /fa/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) متد

خلاصه زوم [Section](../../section/) عنصر را برای بخش داده شده برمی‌گرداند.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) برای یافتن [ISection](../../isection/) |

### مقدار بازگشتی

[ISummaryZoomSection](../../isummaryzoomsection/) یا null اگر مجموعه عنصری برای این بخش ندارد.

## توضیحات

این مثال دریافت عنصر Summary Zoom [Section](../../section/) بر اساس اندیس را نشان می‌دهد:
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
* کلاس [ISummaryZoomSectionCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)