---
title: Clear()
second_title: مرجع API Aspose.Slides برای C++
description: تمام اشیاء SummaryZoomSection را از مجموعه حذف می‌کند.
type: docs
weight: 66
url: /fa/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() متد

تمام اشیاء [SummaryZoomSection](../../summaryzoomsection/) را از مجموعه حذف می‌کند.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## توضیحات

مثال نحوه دریافت عنصر Summary Zoom [Section](../../section/) با اندیس را نشان می‌دهد:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## همچنین ببینید

* کلاس [ISummaryZoomSectionCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)