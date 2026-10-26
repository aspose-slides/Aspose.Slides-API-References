---
title: set_BeginningCharacter()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "Delimiter Beginning Character กำหนดอักขระ delimiter ที่เป็นจุดเริ่มต้นหรือเปิด. Delimiter ทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่น วงเล็บ, วงเล็บเหลี่ยม, และปีกกา. ค่าเริ่มต้น: '('."
type: docs
weight: 27
url: /th/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) เมธอด

Delimiter Beginning Character กำหนดอักขระ delimiter ที่เป็นจุดเริ่มต้นหรือเปิด. Delimiter ทางคณิตศาสตร์คืออักขระที่ล้อมรอบเช่น วงเล็บ, วงเล็บสี่เหลี่ยม, และปีกกา. ค่าเริ่มต้นคือ '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## ดูเพิ่มเติม

* คลาส [MathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)