---
title: get_BeginningCharacter()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "Delimiter Beginning Character ระบุอักขระตัวคั่นที่เป็นจุดเริ่มต้นหรือเปิดอักขระตัวคั่น ตัวคั่นทางคณิตศาสตร์คืออักขระที่ล้อมรอบเช่นวงเล็บ, วงเล็บเหลี่ยม, และวงเล็บโค้ง ค่าเริ่มต้น: '('."
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() เมธอด

Delimiter Beginning Character ระบุอักขระตัวคั่นที่เป็นจุดเริ่มต้นหรือเปิดอักขระตัวคั่น ตัวคั่นทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่นวงเล็บ, วงเล็บเหลี่ยม, และวงเล็บโค้ง ค่าเริ่มต้น: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
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