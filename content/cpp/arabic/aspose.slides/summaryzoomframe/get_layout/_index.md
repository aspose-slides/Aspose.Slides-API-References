---
title: get_Layout()
second_title: مرجع Aspose.Slides للغة C++ API
description: يحصل على تخطيط أقسام ملخص التكبير في الإطار. القيمة الافتراضية هي GridLayout.
type: docs
weight: 1
url: /ar/aspose.slides/summaryzoomframe/get_layout/
---
## طريقة SummaryZoomFrame::get_Layout()


يحصل على تخطيط أقسام ملخص التكبير في الإطار. القيمة الافتراضية هي GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## ملاحظات


يوضح المثال الحصول على العنصر [Section](../../section/) في ملخص التكبير عن طريق الفهرس:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## انظر أيضاً

* تعداد [ZoomLayout](../../zoomlayout/)
* فئة [SummaryZoomFrame](../)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)