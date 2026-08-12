---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คุณลักษณะนี้ระบุว่าผลกระทบจะทำซ้ำจนถึงตอนจบของสไลด์หรือไม่ เขียนเป็น bool.
type: docs
weight: 144
url: /th/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) เมธอด


คุณลักษณะนี้ระบุว่าผลกระทบจะทำซ้ำจนถึงตอนจบของสไลด์หรือไม่ เขียนเป็น **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// ดึงลำดับของเอฟเฟกต์สำหรับสไลด์แรก
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// ดึงเอฟเฟกต์แรกของลำดับหลัก.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// เปลี่ยน Timing/Repeat ของเอฟเฟกต์เป็น "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## ดูเพิ่มเติม

* คลาส [Timing](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)