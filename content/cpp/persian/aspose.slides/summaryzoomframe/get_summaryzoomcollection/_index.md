---
title: get_SummaryZoomCollection()
second_title: مرجع API Aspose.Slides برای C++
description: دریافت ISummaryZoomSectionCollection برای شیء Summary Zoom Frame.
type: docs
weight: 14
url: /fa/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() متد

دریافت [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) برای شیء Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## توضیحات

مثال نشان می‌دهد که عنصر [Section](../../section/) Summary Zoom را بر اساس شاخص دریافت کنید:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* کلاس [SummaryZoomFrame](../)
* فضای‌نامی [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)