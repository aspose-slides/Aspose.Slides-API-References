---
title: get_NoBreak()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ไม่มีการตัดบรรทัด. คุณสมบัตินี้ระบุคุณสมบัติ \"unbreakable\" บนกล่องวัตถุ. เมื่อเป็น true, จะไม่มีการตัดบรรทัดภายในกล่อง. สิ่งนี้อาจสำคัญสำหรับตัวจำลองตัวดำเนินการที่ประกอบด้วยตัวดำเนินการไบนารีมากกว่าหนึ่งตัว. เมื่อไม่ได้ระบุองค์ประกอบนี้, การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง. ค่าเริ่มต้น: true"
type: docs
weight: 40
url: /th/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() เมธอด


ไม่มีการตัดบรรทัด. คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ. เมื่อเป็น true, จะไม่มีการตัดบรรทัดภายในกล่อง. สิ่งนี้อาจสำคัญสำหรับตัวจำลองตัวดำเนินการที่ประกอบด้วยตัวดำเนินการไบนารีมากกว่าหนึ่งตัว. เมื่อไม่ได้ระบุองค์ประกอบนี้, การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง. ค่าเริ่มต้น: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## ดูเพิ่มเติม

* คลาส [IMathBox](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)