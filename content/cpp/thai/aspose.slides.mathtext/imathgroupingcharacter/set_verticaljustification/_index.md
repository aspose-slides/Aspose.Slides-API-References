---
title: set_VerticalJustification()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "การจัดตำแหน่งแนวตั้งของตัวอักษรกลุ่ม กำหนดการจัดแนวของอ็อบเจกต์สัมพันธ์กับ baseline ตัวอย่างเช่น เมื่อกลุ่มอักขระอยู่เหนืออ็อบเจกต์ VerticalJustification ของ Top หมายถึงส่วนบนของอ็อบเจกต์ตกบน baseline; เมื่อ VerticalJustification ถูกตั้งเป็น Bottom ส่วนล่างของอ็อบเจกต์อยู่บน baseline ค่าเริ่มต้น: Bottom สำหรับ Position=Top และ Top สำหรับ Position=Bottom"
type: docs
weight: 79
url: /th/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) เมธอด

การจัดตำแหน่งแนวตั้งของตัวอักษรกลุ่ม กำหนดการจัดแนวของอ็อบเจกต์สัมพันธ์กับ baseline ตัวอย่างเช่น เมื่อกลุ่มอักขระอยู่เหนืออ็อบเจกต์ VerticalJustification ของ Top หมายถึงส่วนบนของอ็อบเจกต์ตกบน baseline; เมื่อ VerticalJustification ถูกตั้งเป็น Bottom ส่วนล่างของอ็อบเจกต์อยู่บน baseline ค่าเริ่มต้น: Bottom สำหรับ Position=Top และ Top สำหรับ Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## ดูเพิ่มเติม

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* คลาส [IMathGroupingCharacter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)