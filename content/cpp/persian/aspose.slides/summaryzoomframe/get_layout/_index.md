---
title: get_Layout()
second_title: مرجع API Aspose.Slides برای C++
description: طرح‌بندی بخش‌های زوم خلاصه را در فریم دریافت می‌کند. مقدار پیش‌فرض GridLayout است.
type: docs
weight: 1
url: /fa/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() متد


طرح‌بندی بخش‌های زوم خلاصه را در فریم دریافت می‌کند. مقدار پیش‌فرض GridLayout است.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## توضیحات


نمونه نشان می‌دهد که چگونه عنصر Summary Zoom [Section](../../section/) را بر اساس اندیس دریافت می‌کنید: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## همچنین ببینید

* Enum [ZoomLayout](../../zoomlayout/)
* Class [SummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)