---
title: CreateMathBorderBox()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างกล่องขอบคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method

สร้างกล่องขอบคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบคณิตศาสตร์ที่จะนำไปใช้กับ border box |

### ค่าที่คืน

องค์ประกอบ border box ใหม่

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method

สร้างกล่องขอบคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบคณิตศาสตร์ที่จะนำไปใช้กับ border box |
| hideTop | **bool** | ซ่อนขอบบน |
| hideBottom | **bool** | ซ่อนขอบล่าง |
| hideLeft | **bool** | ซ่อนขอบซ้าย |
| hideRight | **bool** | ซ่อนขอบขวา |
| strikethroughHorizontal | **bool** | ขีดฆ่าแนวนอนของ Border Box |
| strikethroughVertical | **bool** | ขีดฆ่าแนวตั้งของ Border Box |
| strikethroughBottomLeftToTopRight | **bool** | ขีดฆ่า Border Box จากด้านล่างซ้ายไปด้านบนขวา |
| strikethroughTopLeftToBottomRight | **bool** | ขีดฆ่า Border Box จากด้านบนซ้ายไปด้านล่างขวา |

### ค่าที่คืน

องค์ประกอบ border box ใหม่

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBorderBox](../../imathborderbox/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBorderBoxFactory](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)