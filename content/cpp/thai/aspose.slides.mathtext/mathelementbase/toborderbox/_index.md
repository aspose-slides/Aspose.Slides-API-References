---
title: ToBorderBox()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: วางองค์ประกอบนี้ใน border-box
type: docs
weight: 248
url: /th/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() method

วางองค์ประกอบนี้ใน border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```

### ค่าที่คืน

border-box ที่มีองค์ประกอบนี้วางอยู่ภายใน

## หมายเหตุ

ตัวอย่าง:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) method

วางองค์ประกอบนี้ใน border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hideTop | **bool** | ซ่อนขอบบน |
| hideBottom | **bool** | ซ่อนขอบล่าง |
| hideLeft | **bool** | ซ่อนขอบซ้าย |
| hideRight | **bool** | ซ่อนขอบขวา |
| strikethroughHorizontal | **bool** | เส้นทับของ Border Box แนวนอน |
| strikethroughVertical | **bool** | เส้นทับของ Border Box แนวตั้ง |
| strikethroughBottomLeftToTopRight | **bool** | เส้นทับของ Border Box จากด้านล่างซ้ายไปด้านบนขวา |
| strikethroughTopLeftToBottomRight | **bool** | เส้นทับของ Border Box จากด้านบนซ้ายไปด้านล่างขวา |

### ค่าที่คืน

border-box ที่มีองค์ประกอบนี้วางอยู่ภายใน

## หมายเหตุ

ตัวอย่าง:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBorderBox](../../imathborderbox/)
* คลาส [MathElementBase](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)