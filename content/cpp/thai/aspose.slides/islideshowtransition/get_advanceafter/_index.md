---
title: get_AdvanceAfter()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์จะย้ายไปสไลด์ถัดไปหลังจากระยะเวลาหนึ่ง. อ่าน bool.
type: docs
weight: 105
url: /th/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() เมธอด

แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์จะย้ายไปสไลด์ถัดไปหลังจากระยะเวลาหนึ่ง. อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// ดึงการเปลี่ยนสไลด์แรก
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// ตรวจสอบว่าธง Advance Slide After ถูกตั้งค่าไว้หรือไม่
if (slideTransition->get_AdvanceAfter())
{
    // ดึงค่าเวลา Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## ดูเพิ่มเติม

* คลาส [ISlideShowTransition](../)
* เนมสเปส [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)