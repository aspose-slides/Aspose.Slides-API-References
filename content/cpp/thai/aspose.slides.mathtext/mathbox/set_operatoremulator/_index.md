---
title: set_OperatorEmulator()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ตัวจำลองตัวดำเนินการ เมื่อเป็น true กล่องและเนื้อหาภายในทำงานเหมือนตัวดำเนินการเดียวและสืบทอดคุณสมบัติของตัวดำเนินการ ซึ่งหมายความว่า ตัวอักษรสามารถทำหน้าที่เป็นจุดสำหรับการตัดบรรทัดและสามารถจัดแนวกับตัวดำเนินการอื่น ๆ ตัวจำลองตัวดำเนินการมักใช้เมื่อ glyph หนึ่งหรือหลายตัวรวมกันเป็นตัวดำเนินการ เช่น '==' ค่าเริ่มต้น: false"
type: docs
weight: 27
url: /th/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) เมธอด

ตัวจำลองตัวดำเนินการ เมื่อเป็น true กล่องและเนื้อหาภายในจะทำงานเหมือนตัวดำเนินการเดียวและสืบทอดคุณสมบัติของตัวดำเนินการ ซึ่งหมายความว่า ตัวอักษรสามารถทำหน้าที่เป็นจุดสำหรับการตัดบรรทัดและสามารถจัดแนวกับตัวดำเนินการอื่น ๆ ตัวจำลองตัวดำเนินการมักใช้เมื่อ glyph หนึ่งหรือหลายตัวรวมกันเป็นตัวดำเนินการ เช่น '==' ค่าเริ่มต้น: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
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