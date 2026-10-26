---
title: GetRect()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับพิกัดของสี่เหลี่ยมที่ล้อมกรอบส่วน. สี่เหลี่ยมนี้รวมทุกบรรทัดของข้อความในส่วน, รวมถึงบรรทัดที่ว่างเปล่าด้วย.
type: docs
weight: 92
url: /th/aspose.slides/portion/getrect/
---
## Portion::GetRect() เมธอด


รับพิกัดของสี่เหลี่ยมที่ล้อมกรอบส่วน. สี่เหลี่ยมนี้รวมทุกบรรทัดของข้อความในส่วน, รวมถึงบรรทัดที่ว่างเปล่าด้วย.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::Rectangle, 50.0f, 50.0f, 200.0f, 50.0f);

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Clear();
auto portion0 = System::MakeObject<Portion>(u"Some text");
auto portion1 = System::MakeObject<Portion>(u"GetRect text");

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion0);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion1);

auto rect = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(1)->GetRect();
// ...
```

## ดูเพิ่มเติม

* คลาส [RectangleF](../../../system.drawing/rectanglef/)
* คลาส [Portion](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)