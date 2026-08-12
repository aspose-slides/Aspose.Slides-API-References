---
title: get_OperatorEmulator()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "Operator Emulator. เมื่อเป็นจริง, กล่องและเนื้อหาภายในทำหน้าที่เหมือนโอเปอเรเตอร์เดียวและสืบทอดคุณสมบัติของโอเปอเรเตอร์. ซึ่งหมายความว่า, ตัวอย่างเช่น, ตัวอักษรสามารถทำหน้าที่เป็นจุดสำหรับการตัดบรรทัดและสามารถจัดตำแหน่งกับโอเปอเรเตอร์อื่นได้. Operator Emulators มักใช้เมื่อหนึ่งหรือหลาย glyphs รวมกันเป็นโอเปอเรเตอร์, เช่น '=='. ค่าเริ่มต้น: false"
type: docs
weight: 14
url: /th/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() เมธอด

Operator Emulator. เมื่อเป็นจริง, กล่องและเนื้อหาภายในทำหน้าที่เหมือนโอเปอเรเตอร์เดียวและสืบทอดคุณสมบัติของโอเปอเรเตอร์. ซึ่งหมายความว่า, ตัวอย่างเช่น, ตัวอักษรสามารถทำหน้าที่เป็นจุดสำหรับการตัดบรรทัดและสามารถจัดตำแหน่งกับโอเปอเรเตอร์อื่นได้. Operator Emulators มักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็นโอเปอเรเตอร์, เช่น '=='. ค่าเริ่มต้น: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## ดูเพิ่มเติม

* คลาส [MathBox](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)