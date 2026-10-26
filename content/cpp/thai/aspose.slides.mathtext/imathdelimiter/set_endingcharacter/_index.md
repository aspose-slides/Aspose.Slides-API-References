---
title: set_EndingCharacter()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "Delimiter Ending Character ระบุอักขระตัวคั่นที่เป็นอักขระสิ้นสุดหรืออักขระปิด ตัวคั่นทางคณิตศาสตร์คืออักขระที่ล้อมรอบ เช่น วงเล็บ, วงเหลี่ยมเหลี่ยม, และเครื่องหมายปีกกา ค่าปริยายคือ ')'."
type: docs
weight: 79
url: /th/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) เมธอด

Delimiter Ending Character ระบุอักขระตัวคั่นที่เป็นอักขระสิ้นสุดหรืออักขระปิด ตัวคั่นทางคณิตศาสตร์คืออักขระที่ล้อมรอบ เช่น วงเล็บ, วงเหลี่ยมเหลี่ยม, และเครื่องหมายปีกกา ค่าปริยายคือ ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
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