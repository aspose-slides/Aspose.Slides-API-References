---
title: WriteShapeStart()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เรียกก่อนการเรนเดอร์ของ shape. ถูกเรียกหนึ่งครั้งต่อแต่ละ shape. หากฟังก์ชันนี้เขียนอะไรลงไปใน generator, การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น, ส่วน HTML ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มต้นเหนือภาพก่อนหน้า.
type: docs
weight: 53
url: /th/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) เมธอด

ถูกเรียกก่อนการเรนเดอร์ของ shape. ถูกเรียกหนึ่งครั้งต่อแต่ละ shape. ถ้าฟังก์ชันนี้เขียนอะไรลงไปใน generator, การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น, ส่วน HTML ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มต้นเหนือภาพก่อนหน้า.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | วัตถุผลลัพธ์. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) ซึ่งกำลังจะเรนเดอร์. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IHtmlGenerator](../../ihtmlgenerator/)
* คลาส [IShape](../../../aspose.slides/ishape/)
* คลาส [IHtmlFormattingController](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)