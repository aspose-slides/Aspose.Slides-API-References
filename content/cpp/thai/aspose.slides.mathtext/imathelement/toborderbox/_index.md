---
title: ToBorderBox()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: วางองค์ประกอบนี้ในกล่องขอบ
type: docs
weight: 261
url: /th/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() เมธอด

วางองค์ประกอบนี้ในกล่องขอบ

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```

### ค่าที่ส่งคืน

กล่องขอบที่มีองค์ประกอบนี้อยู่ภายใน
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) เมธอด

วางองค์ประกอบนี้ในกล่องขอบ

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hideTop | **bool** | ซ่อนขอบด้านบน |
| hideBottom | **bool** | ซ่อนขอบด้านล่าง |
| hideLeft | **bool** | ซ่อนขอบด้านซ้าย |
| hideRight | **bool** | ซ่อนขอบด้านขวา |
| strikethroughHorizontal | **bool** | เส้นขีดฆ่าตามแนวนอนของกรอบขอบ |
| strikethroughVertical | **bool** | เส้นขีดฆ่าตามแนวตั้งของกรอบขอบ |
| strikethroughBottomLeftToTopRight | **bool** | เส้นขีดฆ่าจากมุมล่างซ้ายไปมุมบนขวาของกรอบขอบ |
| strikethroughTopLeftToBottomRight | **bool** | เส้นขีดฆ่าจากมุมบนซ้ายไปมุมล่างขวาของกรอบขอบ |

### ค่าที่ส่งคืน

กล่องขอบที่มีองค์ประกอบนี้อยู่ภายใน
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)