---
title: AddSummaryZoomSection()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شیء جدید Summary Zoom Section ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید
type: docs
weight: 53
url: /fa/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) متد

یک شیء جدید Summary Zoom [Section](../../section/) ایجاد می‌کند و آن را به مجموعه اضافه می‌گیرد

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) برای یک عنصر جدید Summary Zoom [Section](../../section/) [ISection](../../isection/) |

### مقدار بازگشتی

عنصر [ISummaryZoomFrame](../../isummaryzoomframe/) اضافه شد
## یادداشت‌ها

اگر یک عنصر برای این بخش قبلاً در مجموعه وجود داشته باشد، عنصر موجود بازگردانده می‌شود. 

این مثال نحوه دریافت عنصر Summary Zoom [Section](../../section/) بر مبنای شاخص را نشان می‌دهد: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISummaryZoomSection](../../isummaryzoomsection/)
* کلاس [ISection](../../isection/)
* کلاس [SummaryZoomSectionCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)