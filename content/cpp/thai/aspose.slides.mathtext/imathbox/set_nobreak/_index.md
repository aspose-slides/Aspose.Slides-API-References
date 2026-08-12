---
title: set_NoBreak()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "ไม่มีการแบ่งบรรทัด คุณสมบัตินี้ระบุคุณสมบัติ \"unbreakable\" บนกล่องวัตถุ เมื่อเป็น true จะไม่มีการแบ่งบรรทัดภายในกล่อง สิ่งนี้อาจสำคัญสำหรับตัวจำลองโอเปอเรเตอร์ที่ประกอบด้วยโอเปอร์เรเตอร์ไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุองค์ประกอบนี้ การแบ่งบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true"
type: docs
weight: 53
url: /th/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) เมธอด

ไม่มีการแบ่งบรรทัด คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ เมื่อค่าเป็น true จะไม่มีการแบ่งบรรทัดภายในกล่อง สิ่งนี้อาจสำคัญสำหรับการจำลองตัวดำเนินการที่ประกอบด้วยตัวดำเนินการแบบไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุองค์ประกอบนี้ การแบ่งบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
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