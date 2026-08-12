---
title: get_VerticalJustification()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "การจัดแนวแนวตั้งของอักขระกลุ่ม ระบุการจัดตำแหน่งของวัตถุเทียบกับเส้นฐาน ตัวอย่างเช่น เมื่อตัวอักขระกลุ่มอยู่เหนือวัตถุ VerticalJustification ของ Top หมายถึงด้านบนของวัตถุตั้งอยู่บนเส้นฐาน; เมื่อ VerticalJustification ตั้งเป็น Bottom ด้านล่างของวัตถุอยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom สำหรับ Position=Top และ Top สำหรับ Position=Bottom"
type: docs
weight: 66
url: /th/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() เมธอด

การจัดแนวแนวตั้งของอักขระกลุ่ม ระบุการจัดตำแหน่งของวัตถือเทียบกับเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถุ VerticalJustification ของ Top หมายถึงด้านบนของวัตถุตกบนเส้นฐาน; เมื่อ VerticalJustification ถูกตั้งเป็น Bottom ด้านล่างของวัตถุอยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom สำหรับ Position=Top และ Top สำหรับ Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## ดูเพิ่มเติม

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* คลาส [MathGroupingCharacter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)