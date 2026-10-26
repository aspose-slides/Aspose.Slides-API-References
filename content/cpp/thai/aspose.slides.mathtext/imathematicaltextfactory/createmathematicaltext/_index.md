---
title: CreateMathematicalText()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่า
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() เมธอด


สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่า

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```


### ค่าที่ส่งกลับ

Mathematical Text ใหม่

## IMathematicalTextFactory::CreateMathematicalText(char16_t) เมธอด


สร้างองค์ประกอบข้อความคณิตศาสตร์ด้วยค่าที่ระบุ

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathSymbol | char16_t | สัญลักษณ์เดียวที่ใช้เป็นค่าข้อความ |

### ค่าที่ส่งกลับ

Mathematical Text ใหม่

## IMathematicalTextFactory::CreateMathematicalText(System::String) เมธอด


สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่าด้วยค่าที่ระบุ

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | ค่าข้อความ |

### ค่าที่ส่งกลับ

Mathematical Text ใหม่

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) เมธอด


สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่าด้วยค่าที่ระบุและคุณสมบัติการจัดรูปแบบ

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | ค่าข้อความ |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | การตั้งค่ารูปแบบข้อความ |

### ค่าที่ส่งกลับ

Mathematical Text ใหม่

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathematicalText](../../imathematicaltext/)
* คลาส [IMathematicalTextFactory](../)
* คลาส [String](../../../system/string/)
* คลาส [IPortionFormat](../../../aspose.slides/iportionformat/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)