---
title: WriteShapeEnd()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ถูกเรียกก่อนการเรนเดอร์ของรูปร่าง. ถูกเรียกหนึ่งครั้งต่อแต่ละรูปร่าง. หากฟังก์ชันนี้เขียนอะไรลงไปยังตัวสร้าง การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น ส่วน HTML fragment ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มต้นเหนือภาพก่อนหน้า.
type: docs
weight: 66
url: /th/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) เมธอด

เรียกใช้ก่อนการแสดงผลของรูปร่าง เรียกใช้หนึ่งครั้งต่อแต่ละรูปร่าง หากฟังก์ชันนี้เขียนอะไรลงในตัวสร้าง การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น ส่วน HTML fragment ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มต้นเหนือภาพเดิม

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | อ็อบเจ็กต์ผลลัพธ์ |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) ที่ทำการแสดงผลเป็นอันสุดท้าย |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IHtmlGenerator](../../ihtmlgenerator/)
* คลาส [IShape](../../../aspose.slides/ishape/)
* คลาส [IHtmlFormattingController](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)