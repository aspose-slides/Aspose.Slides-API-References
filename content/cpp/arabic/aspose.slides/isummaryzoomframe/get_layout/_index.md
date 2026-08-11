---
title: get_Layout()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على تخطيط أقسام التكبير الملخص في الإطار. القيمة الافتراضية هي GridLayout.
type: docs
weight: 1
url: /ar/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() طريقة

يحصل على تخطيط أقسام التكبير الملخص في الإطار. القيمة الافتراضية هي GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## ملاحظات

يوضح المثال طريقة الحصول على عنصر [Section](../../section/) الخاص بالتكبير الملخص بواسطة الفهرس:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## انظر أيضًا

* تعداد [ZoomLayout](../../zoomlayout/)
* فئة [ISummaryZoomFrame](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)