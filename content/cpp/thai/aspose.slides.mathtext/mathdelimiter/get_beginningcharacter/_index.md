---
title: get_BeginningCharacter()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: "อักขระเริ่มต้นของตัวคั่นระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น. ตัวคั่นทางคณิตศาสตร์คืออักขระที่ล้อมรอบเช่น วงเล็บ, วงเหลี่ยม, และวงโค้ง. ค่าเริ่มต้น: '('."
type: docs
weight: 14
url: /th/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() เมธอด

Delimiter Beginning Character ระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น. ตัวคั่นทางคณิตศาสตร์คืออักขระที่ล้อมรอบเช่น วงเล็บ, วงเหลี่ยม, และวงโค้ง. ค่าเริ่มต้น: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
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