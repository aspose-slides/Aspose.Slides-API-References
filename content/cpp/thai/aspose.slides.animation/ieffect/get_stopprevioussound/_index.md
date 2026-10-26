---
title: get_StopPreviousSound()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คุณลักษณะนี้ระบุว่าผลกระทบการเคลื่อนไหวหยุดเสียงก่อนหน้าหรือไม่ อ่าน bool.
type: docs
weight: 196
url: /th/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() เมธอด

คุณลักษณะนี้ระบุว่าผลกระทบการเคลื่อนไหวหยุดเสียงก่อนหน้าหรือไม่ อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
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