---
title: get_SummaryZoomCollection()
second_title: مرجع API Aspose.Slides برای C++
description: دریافت ISummaryZoomSectionCollection برای شیء Summary Zoom Frame.
type: docs
weight: 14
url: /fa/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() متد


دریافت [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) برای شیء Summary Zoom Frame.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## توضیحات


مثال نشان می‌دهد که دریافت عنصر [Section](../../section/) Summary Zoom بر اساس اندیس:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* کلاس [ISummaryZoomFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)