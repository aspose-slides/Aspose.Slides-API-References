---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอักขระการจัดกลุ่มคณิตศาสตร์
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) เมธอด

สร้างอักขระการจัดกลุ่มคณิตศาสตร์

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อิลิเมนต์คณิตศาสตร์ที่ใช้สำหรับใส่อักขระการจัดกลุ่ม |
| character | char16_t | อักขระการจัดกลุ่ม |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | ตำแหน่งของอักขระการจัดกลุ่ม |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | การจัดแนวแนวตั้ง |

### ค่ารีเทิร์น

อิลิเมนต์อักขระการจัดกลุ่มใหม่

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) เมธอด

สร้างอักขระการจัดกลุ่มคณิตศาสตร์

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อิลิเมนต์คณิตศาสตร์ที่ใช้สำหรับใส่อักขระการจัดกลุ่ม |

### ค่ารีเทิร์น

อิลิเมนต์อักขระการจัดกลุ่มใหม่

## ดูเพิ่มเติม

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathGroupingCharacter](../../imathgroupingcharacter/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathGroupingCharacterFactory](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)