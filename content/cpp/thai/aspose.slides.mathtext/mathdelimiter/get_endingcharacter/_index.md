---
title: get_EndingCharacter()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ตัวอักษรจบของ Delimiter ระบุอักขระที่ใช้เป็นจุดจบหรือปิดของ delimiter. Delimiter ทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่น วงเล็บ, วงเล็บสี่เหลี่ยม, และวงเล็บปีกกา. ค่าเริ่มต้น: ')'."
type: docs
weight: 66
url: /th/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() เมธอด


Delimiter Ending Character ระบุอักขระที่ใช้เป็นจุดจบหรือปิดของ delimiter. Delimiter ทางคณิตศาสตร์คืออักขระที่ล้อมรอบเช่น วงเล็บ, วงเล็บสี่เหลี่ยม, และวงเล็บปีกกา. ค่าเริ่มต้น: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## ดูเพิ่มเติม

* คลาส [MathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)