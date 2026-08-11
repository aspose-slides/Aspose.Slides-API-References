---
title: get_Slides()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: نطاق الشرائح
type: docs
weight: 118
url: /ar/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const طريقة

[Slides](../../) نطاق

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [SlidesRange](../../slidesrange/)
* فئة [SlideShowSettings](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)