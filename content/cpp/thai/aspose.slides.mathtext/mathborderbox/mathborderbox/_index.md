---
title: MathBorderBox()
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: สร้างองค์ประกอบ MathBorderBox พร้อมขอบสี่เหลี่ยมผืนผ้า
type: docs
weight: 222
url: /th/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) คอนสตรัคเตอร์

สร้าง [MathBorderBox](../) พร้อมขอบสี่เหลี่ยมผืนผ้า

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบฐานที่ใช้กับ border box. สามารถเป็นค่า null ได้. |

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) คอนสตรัคเตอร์

สร้าง [MathBorderBox](../)

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบฐานที่ใช้กับ border box |
| hideTop | **bool** | ซ่อนขอบบน |
| hideBottom | **bool** | ซ่อนขอบล่าง |
| hideLeft | **bool** | ซ่อนขอบซ้าย |
| hideRight | **bool** | ซ่อนขอบขวา |
| strikethroughHorizontal | **bool** | ขีดเส้นแนวนอน |
| strikethroughVertical | **bool** | ขีดเส้นแนวตั้ง |
| strikethroughBottomLeftToTopRight | **bool** | ขีดเส้นจากมุมล่างซ้ายถึงมุมบนขวา |
| strikethroughTopLeftToBottomRight | **bool** | ขีดเส้นจากมุมบนซ้ายถึงมุมล่างขวา |

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBorderBox](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)