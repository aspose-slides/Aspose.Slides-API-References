---
title: set_BeginningCharacter()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "Delimiter Beginning Character ระบุอักขระตัวคั่นที่เป็นจุดเริ่มต้นหรือเปิดอักขระ. ตัวคั่นทางคณิตศาสตร์คืออักขระที่ล้อมรอบเช่น วงเล็บ, วงสี่เหลี่ยมและ วงโค้ง. ค่าปริยายคือ '('."
type: docs
weight: 27
url: /th/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) เมธอด


Delimiter Beginning Character ระบุอักขระตัวคั่นที่เป็นจุดเริ่มต้นหรือเปิดอักขระ ตัวคั่นทางคณิตศาสตร์คืออักขระที่ล้อมรอบเช่น วงเล็บ, วงสี่เหลี่ยมและ วงโค้ง. ค่าปริยายคือ '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## หมายเหตุ


ตัวอย่าง:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## ดูเพิ่มเติม

* คลาส [IMathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)