---
title: MathGroupingCharacter()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter ด้วยอักขระการจัดกลุ่มเริ่มต้น U+23DF (วงเล็บโค้งล่าง)
type: docs
weight: 92
url: /th/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของคลาส [MathGroupingCharacter](../) ด้วยอักขระการจัดกลุ่มเริ่มต้น U+23DF (BOTTOM CURLY BRACKET)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อิลิเมนต์พื้นฐานที่บาร์ถูกนำไปใช้ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของคลาส [MathGroupingCharacter](../).

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อิลิเมนต์พื้นฐานที่บาร์ถูกนำไปใช้ |
| character | char16_t | อักขระการจัดกลุ่ม |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | ตำแหน่งของอักขระการจัดกลุ่ม |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | การจัดแนวแนวตั้งของอักขระกลุ่ม |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## ดูเพิ่มเติม

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathGroupingCharacter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)