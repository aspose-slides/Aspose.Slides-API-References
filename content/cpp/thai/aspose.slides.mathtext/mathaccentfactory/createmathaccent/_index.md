---
title: CreateMathAccent()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างการเน้นคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่กำหนดโดยใช้ค่าตัวอักษรเน้นเริ่มต้น
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) เมธอด

สร้างการเน้นคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่กำหนดโดยใช้ค่าตัวอักษรเน้นเริ่มต้น

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบคณิตศาสตร์ที่ใช้ในการเน้น |
| accentCharacter | char16_t | ตัวอักษรเน้น |

### ค่าที่คืน

การเน้นคณิตศาสตร์ใหม่

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) เมธอด

สร้างการเน้นคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่กำหนด

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบคณิตศาสตร์ที่ใช้ในการเน้น |
| accentCharacter | char16_t | ตัวอักษรเน้น |

### ค่าที่คืน

การเน้นคณิตศาสตร์ใหม่

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathAccent](../../imathaccent/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathAccentFactory](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)