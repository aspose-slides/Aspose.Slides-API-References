---
title: set_StopPreviousSound()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แอตทริบิวต์นี้กำหนดว่าผลกระทบการแอนิเมชันจะหยุดเสียงก่อนหน้าหรือไม่ เขียนเป็น bool.
type: docs
weight: 209
url: /th/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) เมธอด

แอตทริบิวต์นี้กำหนดว่าผลกระทบการแอนิเมชันหยุดเสียงก่อนหน้าหรือไม่ เขียนเป็น **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## หมายเหตุ


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// รับเอฟเฟกต์แรกของสไลด์แรก.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// รับเอฟเฟกต์แรกของสไลด์ที่สอง.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // เปลี่ยน Enhancements/Sound ของเอฟเฟกต์ที่สองเป็น "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## ดูเพิ่มเติม

* คลาส [IEffect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)