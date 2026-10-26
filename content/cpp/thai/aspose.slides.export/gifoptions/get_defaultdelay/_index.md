---
title: get_DefaultDelay()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "รับค่าเวลาเลื่อนชั่วคราวเริ่มต้น [ms]. ค่าดังกล่าวจะถูกใช้หากเมธอด ISlideShowTransition::set_AdvanceAfterTime() ไม่ได้ถูกเรียกใช้. ค่าเริ่มต้นคือ 1000."
type: docs
weight: 79
url: /th/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() method


รับค่าเวลาเลื่อนชั่วคราวเริ่มต้น [ms]. ค่าดังกล่าวจะถูกใช้หากเมธอด [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) ไม่ได้ถูกเรียกใช้. ค่าตั้งต้นคือ 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
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