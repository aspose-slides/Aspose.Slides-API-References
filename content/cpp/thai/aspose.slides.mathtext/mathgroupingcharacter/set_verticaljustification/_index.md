---
title: set_VerticalJustification()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "การจัดตำแหน่งแนวตั้งของอักขระกลุ่ม ระบุการจัดแนวของอ็อบเจกต์กับเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนืออ็อบเจกต์ VerticalJustification ของ Top หมายความว่าด้านบนของอ็อบเจกต์ตั้งอยู่บนเส้นฐาน; เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom ด้านล่างของอ็อบเจกต์อยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom สำหรับ Position=Top และ Top สำหรับ Position=Bottom"
type: docs
weight: 79
url: /th/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) เมธอด

การจัดตำแหน่งแนวตั้งของอักขระกลุ่ม. ระบุการจัดแนวของวัตถุกับเส้นฐาน. ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถุ VerticalJustification ของ Top หมายความว่าด้านบนของวัตถุตั้งอยู่บนเส้นฐาน; เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom ด้านล่างของวัตถุจะอยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom สำหรับ Position=Top, และ Top สำหรับ Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## ดูเพิ่มเติม

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)