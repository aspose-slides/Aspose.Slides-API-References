---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides สำหรับ API อ้างอิง C++
description: สร้างอักขระการจัดกลุ่มคณิตศาสตร์
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) method


สร้างอักขระการจัดกลุ่มคณิตศาสตร์

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบคณิตศาสตร์ที่จะนำอักขระการจัดกลุ่มมาใช้ |
| character | char16_t | อักขระการจัดกลุ่ม |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | ตำแหน่งของอักขระการจัดกลุ่ม |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | การจัดแนวตั้งแนว |

### ค่าที่คืนกลับ

อิลีเมนต์อักขระการจัดกลุ่มใหม่

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) method


สร้างอักขระการจัดกลุ่มคณิตศาสตร์

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบคณิตศาสตร์ที่จะนำอักขระการจัดกลุ่มมาใช้ |

### ค่าที่คืนกลับ

อิลีเมนต์อักขระการจัดกลุ่มใหม่

## ดูเพิ่มเติม

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)