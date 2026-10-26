---
title: set_Slides()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: نطاق الشرائح
type: docs
weight: 131
url: /ar/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) طريقة


[Slides](../../) نطاق

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## أنظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [SlidesRange](../../slidesrange/)
* فئة [SlideShowSettings](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)