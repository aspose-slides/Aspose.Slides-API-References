---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนกรอบข้อความทั้งหมดบนสไลด์ที่ระบุซึ่งมีข้อความที่กำหนด
type: docs
weight: 66
url: /th/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) เมธอด

คืนค่ากรอบข้อความทั้งหมดบนสไลด์ที่ระบุซึ่งมีข้อความที่กำหนด

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | สไลด์ที่ต้องการค้นหา |
| text | [System::String](../../../system/string/) | ข้อความที่ต้องการค้นหาในกรอบข้อความ |
| checkPlaceholderText | **bool** | ระบุว่าจะรวมกรอบข้อความที่ว่างเปล่า แต่ข้อความตัวแทนมีข้อความค้นหาอยู่หรือไม่ |

### ค่าที่ส่งกลับ

อาร์เรย์ของอ็อบเจ็กต์ [ITextFrame](../../../aspose.slides/itextframe/) ที่มีข้อความที่ระบุ

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ITextFrame](../../../aspose.slides/itextframe/)
* คลาส [IBaseSlide](../../../aspose.slides/ibaseslide/)
* คลาส [String](../../../system/string/)
* คลาส [SlideUtil](../)
* เนมสเปซ [Aspose::Slides::Util](../../)
* ไลบรารี [Aspose.Slides](../../../)