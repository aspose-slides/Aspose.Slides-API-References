---
title: set_AdvanceAfter()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คุณลักษณะนี้ระบุว่าการแสดงสไลด์จะย้ายไปยังสไลด์ต่อไปหลังจากเวลาที่กำหนดหรือไม่ เขียนเป็น bool.
type: docs
weight: 118
url: /th/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) เมธอด

คุณลักษณะนี้ระบุว่าการนำเสนอจะเคลื่อนย้ายไปยังสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่ เขียนเป็น **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// ดึงการเปลี่ยนสไลด์แรก
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// ตรวจสอบว่าธง Advance Slide After ถูกตั้งค่าอยู่หรือไม่
if (slideTransition->get_AdvanceAfter())
{
    // รับค่าเวลาของ Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## ดูเพิ่มเติม

* คลาส [ISlideShowTransition](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)