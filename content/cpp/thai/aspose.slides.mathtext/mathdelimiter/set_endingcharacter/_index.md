---
title: set_EndingCharacter()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "Delimiter Ending Character ระบุอักขระตัวสิ้นสุดหรืออักขระปิดของ delimiter. Delimiters ทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่น วงเล็บ, กรอบเหลี่ยม, และเครื่องหมายปีกกา. ค่าเริ่มต้น: ')'."
type: docs
weight: 79
url: /th/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) เมธอด

Delimiter Ending Character ระบุอักขระตัวสิ้นสุดหรืออักขระปิดของ delimiter ตัว delimiters ทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่น วงเล็บ, กรอบเหลี่ยม, และวงโค้ง. ค่าเริ่มต้น: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## ดูเพิ่มเติม

* คลาส [MathDelimiter](../)
* เนมส페ซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)