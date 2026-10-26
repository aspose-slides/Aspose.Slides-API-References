---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides برای مرجع API C++
description: شیء Summary Zoom Section را از مجموعه حذف می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) متد


شیء Summary Zoom [Section](../../section/) را از مجموعه حذف کنید.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) برای عنصری که [Section](../../section/) Summary Zoom حذف شود [ISection](../../isection/). |
## توضیحات



این مثال نحوه دریافت عنصر Summary Zoom [Section](../../section/) با استفاده از ایندکس را نشان می‌دهد:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## موارد مرتبط

* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISection](../../isection/)
* کلاس [ISummaryZoomSectionCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)