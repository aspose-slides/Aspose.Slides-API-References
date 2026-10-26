---
title: get_EndingCharacter()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "Delimiter Ending Character ระบุอักขระตัวคั่นที่สิ้นสุดหรือปิด. ตัวคั่นทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่น วงเล็บ, กรอบ, และปีกกา. ค่าเริ่มต้น: ')'."
type: docs
weight: 66
url: /th/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() เมธอด

Delimiter Ending Character ระบุอักขระตัวคั่นที่สิ้นสุด หรือปิด ตัวคั่นทางคณิตศาสตร์คืออักขระที่ล้อมรอบ เช่น วงเล็บ, ปีกกา, และวงเล็บเหลี่ยม. ค่าเริ่มต้น: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## ดูเพิ่มเติม

* คลาส [IMathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)