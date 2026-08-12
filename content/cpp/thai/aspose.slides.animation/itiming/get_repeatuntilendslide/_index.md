---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แอตทริบิวต์นี้ระบุว่าผลเอฟเฟกต์จะทำซ้ำจนถึงจบสไลด์ อ่าน bool.
type: docs
weight: 131
url: /th/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() เมธอด


แอตทริบิวต์นี้ระบุว่าผลเอฟเฟกต์จะทำซ้ำจนถึงจบสไลด์หรือไม่ อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// รับลำดับเอฟเฟกต์สำหรับสไลด์แรก
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// รับเอฟเฟกต์แรกของลำดับหลัก.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// เปลี่ยน Timing/Repeat ของเอฟเฟกต์เป็น "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## ดูเพิ่มเติม

* คลาส [ITiming](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)