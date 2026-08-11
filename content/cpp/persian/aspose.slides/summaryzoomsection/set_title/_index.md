---
title: set_Title()
second_title: Aspose.Slides برای مرجع API C++
description: متن عنوان شیء Summary Zoom Section را برمی‌گرداند.
type: docs
weight: 14
url: /fa/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) متد

متن عنوان شیء [Section](../../section/) Summary Zoom را برمی‌گرداند.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
```

## توضیحات

مثال:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [SummaryZoomSection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)