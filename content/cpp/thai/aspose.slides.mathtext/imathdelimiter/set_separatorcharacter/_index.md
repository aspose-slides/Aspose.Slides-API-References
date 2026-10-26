---
title: set_SeparatorCharacter()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ตัวอักษรตัวคั่นสำหรับ Delimiter กำหนดอักขระที่ใช้แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ delimiter ค่าเริ่มต้นคือ '|'."
type: docs
weight: 53
url: /th/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) เมธอด

Delimiter Separator Character กำหนดอักขระที่ใช้แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ delimiter ตัวนี้ ค่าเริ่มต้น: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## ดูเพิ่มเติม

* คลาส [IMathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)