---
title: get_AdvanceAfter()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คุณลักษณะนี้ระบุว่าการสไลด์โชว์จะเลื่อนไปยังสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่ อ่าน bool.
type: docs
weight: 105
url: /th/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() เมธอด


คุณลักษณะนี้ระบุว่าการสไลด์โชว์จะเลื่อนไปยังสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่ อ่าน **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// ดึงการเปลี่ยนสไลด์แรก
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// ตรวจสอบว่าแฟล็ก Advance Slide After ถูกตั้งหรือไม่
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