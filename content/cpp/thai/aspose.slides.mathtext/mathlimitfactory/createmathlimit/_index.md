---
title: CreateMathLimit()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้าง IMathLimit
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) เมธอด


สร้าง [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อาร์กิวเมนต์ฐานเพื่อใช้กับลิมิต |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อิลีเมนต์ลิมิต |
| upperLimit | **bool** | กำหนดตำแหน่งลิมิตด้านบน |

### ค่าที่ส่งคืน

ลิมิตคณิตใหม่

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) เมธอด


สร้าง [IMathLimit](../../imathlimit/) ด้วยลิมิตที่ด้านล่าง

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อาร์กิวเมนต์ฐานเพื่อใช้กับลิมิต |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อิลีเมนต์ลิมิต |

### ค่าที่ส่งคืน

ลิมิตคณิตใหม่

## ดูเพิ่มเติม

* การกำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathLimit](../../imathlimit/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathLimitFactory](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)