---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides برای مرجع API C++
description: شیء Summary Zoom Section را از مجموعه حذف می‌کند.
type: docs
weight: 79
url: /fa/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) متد


شیء Summary Zoom [Section](../../section/) را از مجموعه حذف می‌کند.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) که عنصر Summary Zoom [Section](../../section/) باید حذف شود [ISection](../../isection/). |
## توضیحات



مثال نشان می‌دهد که عنصر Summary Zoom [Section](../../section/) را بر اساس شاخص دریافت می‌کند: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)