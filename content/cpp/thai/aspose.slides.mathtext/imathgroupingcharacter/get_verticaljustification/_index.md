---
title: get_VerticalJustification()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "การจัดตำแหน่งแนวตั้งของอักขระกลุ่ม ระบุการจัดตำแหน่งของวัตถุเทียบกับเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถุ VerticalJustification ของ Top หมายความว่าด้านบนของวัตถุอยู่บนเส้นฐาน; เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom ด้านล่างของวัตถุอยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom สำหรับ Position=Top, และ Top สำหรับ Position=Bottom"
type: docs
weight: 66
url: /th/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() เมธอด

การจัดตำแหน่งแนวตั้งของอักขระกลุ่ม. ระบุการจัดตำแหน่งของวัตถุเทียบกับเส้นฐาน. ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถุ, VerticalJustification ของ Top หมายถึงว่าบนของวัตถุอยู่บนเส้นฐาน; เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom, ส่วนล่างของวัตถุอยู่บนเส้นฐาน Default: Bottom สำหรับ Position=Top, และ Top สำหรับ Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
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