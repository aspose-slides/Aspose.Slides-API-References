---
title: set_NoBreak()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ไม่มีการตัดบรรทัด คุณสมบัตินี้ระบุคุณสมบัติ \"unbreakable\" บนกล่องวัตถุ เมื่อเป็น true จะไม่มีการตัดบรรทัดภายในกล่อง สิ่งนี้อาจสำคัญสำหรับตัวจำลองตัวดำเนินการที่ประกอบด้วยตัวดำเนินการแบบไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุเอเลเมนต์นี้ การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true"
type: docs
weight: 53
url: /th/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) method


ไม่มีการตัดบรรทัด คุณสมบัตินี้ระบุคุณสมบัติ \"unbreakable\" บนกล่องวัตถุ เมื่อเป็น true จะไม่มีการตัดบรรทัดภายในกล่อง สิ่งนี้อาจสำคัญสำหรับตัวจำลองตัวดำเนินการที่ประกอบด้วยตัวดำเนินการแบบไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุเอเลเมนต์นี้ การตัดบรรทัดสามารถเกิดขึ้นภายในกล่องได้ ค่าเริ่มต้น: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
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