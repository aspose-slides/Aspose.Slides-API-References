---
title: get_DefaultDelay()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "รับค่าเวลาหน่วงตั้งต้น [ms]. ค่าดังกล่าวจะถูกใช้หากไม่ได้เรียกวิธี ISlideShowTransition::set_AdvanceAfterTime(). ค่าตั้งต้นคือ 1000."
type: docs
weight: 79
url: /th/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() วิธีการ

รับค่าเวลาหน่วงเวลาตั้งต้น [ms]. ค่าดังกล่าวจะถูกใช้หากไม่ได้เรียกวิธี [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/). ค่าตั้งต้นคือ 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## ดูเพิ่มเติม

* คลาส [IGifOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)