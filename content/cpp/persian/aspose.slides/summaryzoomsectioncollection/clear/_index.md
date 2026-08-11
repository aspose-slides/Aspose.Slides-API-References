---
title: Clear()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام اشیای SummaryZoomSection را از مجموعه حذف می‌کند.
type: docs
weight: 105
url: /fa/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() متد

تمام اشیاء [SummaryZoomSection](../../summaryzoomsection/) را از مجموعه حذف می‌کند.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## توضیحات

این مثال دریافت عنصر Summary Zoom [Section](../../section/) را بر اساس ایندکس نشان می‌دهد:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## مراجع

* کلاس [SummaryZoomSectionCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)