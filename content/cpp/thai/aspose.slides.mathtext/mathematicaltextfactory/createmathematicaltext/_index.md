---
title: CreateMathematicalText()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่า
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() วิธีการ

สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่า

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```

### ค่าที่ส่งกลับ

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) วิธีการ

สร้างองค์ประกอบข้อความคณิตศาสตร์ด้วยค่าที่ระบุ

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathSymbol | char16_t | สัญลักษณ์เดียวที่ใช้เป็นค่าข้อความ |

### ค่าที่ส่งกลับ

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) วิธีการ

สร้างองค์ประกอบข้อความคณิตศาสตร์ที่ว่างด้วยค่าที่ระบุ

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | ค่าข้อความ |

### ค่าที่ส่งกลับ

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) วิธีการ

สร้างองค์ประกอบข้อความคณิตศาสตร์ที่ว่างด้วยค่าที่ระบุและคุณสมบัติการจัดรูปแบบ

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | ค่าข้อความ |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | การตั้งค่ารูปแบบข้อความ |

### ค่าที่ส่งกลับ

new Mathematical Text

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathematicalText](../../imathematicaltext/)
* คลาส [MathematicalTextFactory](../)
* คลาส [String](../../../system/string/)
* คลาส [IPortionFormat](../../../aspose.slides/iportionformat/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)