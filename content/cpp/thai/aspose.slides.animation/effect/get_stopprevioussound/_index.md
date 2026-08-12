---
title: get_StopPreviousSound()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: คุณลักษณะนี้ระบุว่าเอฟเฟกต์แอนิเมชันหยุดเสียงก่อนหน้าหรือไม่ อ่าน bool.
type: docs
weight: 196
url: /th/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() เมธอด


คุณลักษณะนี้ระบุว่าเอฟเฟกต์แอนิเมชันหยุดเสียงก่อนหน้าหรือไม่ อ่าน **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
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