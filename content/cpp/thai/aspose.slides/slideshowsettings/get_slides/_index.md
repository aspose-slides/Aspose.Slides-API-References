---
title: get_Slides()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ช่วงสไลด์
type: docs
weight: 118
url: /th/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const เมธอด


[Slides](../../) ช่วง

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## ดูเพิ่มเติม

* ชนิดกำหนด [SharedPtr](../../../system/sharedptr/)
* คลาส [SlidesRange](../../slidesrange/)
* คลาส [SlideShowSettings](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)