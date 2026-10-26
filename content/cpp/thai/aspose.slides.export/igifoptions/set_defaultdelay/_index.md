---
title: set_DefaultDelay()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "กำหนดเวลาหน่วงเริ่มต้น [ms]. ค่านี้จะถูกใช้หากเมธอด ISlideShowTransition::set_AdvanceAfterTime() ไม่ได้ถูกเรียก. ค่าตั้งต้นคือ 1000."
type: docs
weight: 92
url: /th/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) เมธอด


กำหนดเวลาหน่วงเวลาเริ่มต้น [ms]. ค่านี้จะถูกใช้หากเมธอด [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) ไม่ได้ถูกเรียก. ค่าตั้งต้นคือ 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
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