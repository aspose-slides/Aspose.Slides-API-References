---
title: get_NoBreak()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "ไม่มีการตัดบรรทัด คุณสมบัตินี้ระบุคุณสมบัติ \"unbreakable\" บนกล่องอ็อบเจกต์ เมื่อเป็น true จะไม่มีการตัดบรรทัดใด ๆ เกิดขึ้นภายในกล่อง ซึ่งอาจสำคัญสำหรับอิมูเลเตอร์ตัวดำเนินการที่ประกอบด้วยตัวดำเนินการไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุองค์ประกอบนี้ การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true"
type: docs
weight: 40
url: /th/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() เมธอด

ไม่มีการตัดบรรทัด คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องอ็อบเจกต์ เมื่อเป็น true จะไม่มีการตัดบรรทัดใด ๆ เกิดขึ้นภายในกล่อง ซึ่งอาจสำคัญสำหรับอิมูเลเตอร์ตัวดำเนินการที่ประกอบด้วยตัวดำเนินการไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุองค์ประกอบนี้ การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## ดูเพิ่มเติม

* คลาส [MathBox](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)