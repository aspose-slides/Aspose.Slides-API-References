---
title: get_OperatorEmulator()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "อิมูเลเตอร์ของผู้ดำเนินการ. เมื่อเป็น true, กล่องและเนื้อหาภายในทำงานเป็นผู้ดำเนินการเดียวและสืบทอดคุณสมบัติของผู้ดำเนินการ. ซึ่งหมายความว่า, ตัวอักษรสามารถทำหน้าที่เป็นจุดแบ่งบรรทัดและสามารถจัดตำแหน่งกับผู้ดำเนินการอื่นได้. อิมูเลเตอร์ของผู้ดำเนินการมักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็นผู้ดำเนินการ, เช่น '=='. ค่าเริ่มต้น: false"
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() เมธอด


อิมูเลเตอร์ของผู้ดำเนินการ. เมื่อเป็น true, กล่องและเนื้อหาภายในทำงานเหมือนผู้ดำเนินการเดียวและสืบทอดคุณสมบัติของผู้ดำเนินการ. ซึ่งหมายความว่าตัวอักษรอาจทำหน้าที่เป็นจุดแบ่งบรรทัดและสามารถจัดตำแหน่งกับผู้ดำเนินการอื่นได้. อิมูเลเตอร์ของผู้ดำเนินการมักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็นผู้ดำเนินการ, เช่น '=='. ค่าเริ่มต้น: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## ดูเพิ่มเติม

* คลาส [IMathBox](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)