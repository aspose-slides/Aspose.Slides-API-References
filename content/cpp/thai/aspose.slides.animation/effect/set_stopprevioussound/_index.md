---
title: set_StopPreviousSound()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: คุณลักษณะนี้ระบุว่าผลการเคลื่อนไหวจะหยุดเสียงก่อนหน้าหรือไม่ เขียนเป็น bool.
type: docs
weight: 209
url: /th/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) เมธอด


คุณลักษณะนี้ระบุว่าผลการเคลื่อนไหวจะหยุดเสียงก่อนหน้าหรือไม่ เขียนเป็น **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// ดึงเอฟเฟกต์แรกของสไลด์แรก.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// ดึงเอฟเฟกต์แรกของสไลด์ที่สอง.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // เปลี่ยน Enhancements/Sound ของเอฟเฟกต์ที่สองเป็น "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## ดูเพิ่มเติม

* คลาส [Effect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)