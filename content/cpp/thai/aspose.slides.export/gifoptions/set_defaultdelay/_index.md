---
title: set_DefaultDelay()
second_title: "Aspose.Slides สำหรับ C++ API Reference"
description: "กำหนดเวลาหน่วงเริ่มต้นเป็น [ms] ค่าดังกล่าวจะถูกใช้หากเมธอด ISlideShowTransition::set_AdvanceAfterTime() ไม่ได้ถูกเรียกใช้ ค่าเริ่มต้นคือ 1000."
type: docs
weight: 92
url: /th/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) method


ตั้งค่าช่วงเวลาหน่วงเริ่มต้นเป็น [ms]. ค่าดังกล่าวจะถูกใช้หากเมธอด [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) ไม่ได้ถูกเรียกใช้งาน. ค่าเริ่มต้นคือ 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## ดูเพิ่มเติม

* คลาส [GifOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)