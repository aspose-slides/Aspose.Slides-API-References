---
title: get_Layout()
second_title: Aspose.Slides برای C++ مرجع API
description: چیدمان بخش‌های Summary Zoom را در فریم بر می‌گرداند. مقدار پیش‌فرض GridLayout است.
type: docs
weight: 1
url: /fa/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() متد

چیدمان بخش‌های Summary Zoom را در فریم بر می‌گرداند. مقدار پیش‌فرض GridLayout است.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## توضیحات

مثال نشان می‌دهد که عنصر [Section](../../section/) Summary Zoom را با استفاده از ایندکس دریافت می‌کند:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## مراجع مرتبط

* Enum [ZoomLayout](../../zoomlayout/)
* Class [ISummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)