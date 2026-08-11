---
title: AddSummaryZoomSection()
second_title: Aspose.Slides برای مرجع API C++
description: یک شیء جدید Summary Zoom Section ایجاد می‌کند و آن را به مجموعه اضافه می‌گرداند
type: docs
weight: 14
url: /fa/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) method

یک شیء جدید Summary Zoom [Section](../../section/) ایجاد می‌کند و آن را به مجموعه افزوده می‌شود

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) برای یک عنصر جدید Summary Zoom [Section](../../section/) [ISection](../../isection/) |

### مقدار بازگردانده شده

عنصر [ISummaryZoomFrame](../../isummaryzoomframe/) افزوده شد

## توضیحات

اگر عنصری برای این بخش قبلاً در مجموعه موجود باشد، عنصر موجود بازگردانده می‌شود.

این مثال نشان می‌دهد که چگونه عنصر Summary Zoom [Section](../../section/) را بر حسب اندیس دریافت می‌کنید:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)