---
title: set_AdvanceAfter()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: แอตทริบิวต์นี้ระบุว่า สไลด์โชว์จะเลื่อนไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่ เขียนเป็น bool.
type: docs
weight: 118
url: /th/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) เมธอด

แอตทริบิวต์นี้ระบุว่า สไลด์โชว์จะเลื่อนไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่ เขียนเป็น **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// รับการเปลี่ยนสไลด์แรก
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// ตรวจสอบว่ามีการตั้งค่าสถานะ Advance Slide After หรือไม่
if (slideTransition->get_AdvanceAfter())
{
    // รับค่าเวลา Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## ดูเพิ่มเติม

* คลาส [SlideShowTransition](../)
* เนมสเปซ [Aspose::Slides::SlideShow](../../)
* ไลบรารี [Aspose.Slides](../../../)