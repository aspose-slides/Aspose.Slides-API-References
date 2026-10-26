---
title: get_SpellCheck()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: รับค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าเริ่มต้นคือ false.
type: docs
weight: 599
url: /th/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() วิธี

ได้ค่าที่บ่งชี้ว่าการตรวจสอบการสะกดคำเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัติถูกตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าดีฟอลต์คือ **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงการเปิดใช้แฟล็ก SpellCheck ก่อนบันทึกการนำเสนอ:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// เข้าถึงส่วนข้อความแรกภายในรูปร่างแรกบนสไลด์แรก
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// เปิดใช้งานการตรวจสอบการสะกดสำหรับส่วนข้อความนี้
portion->get_PortionFormat()->set_SpellCheck(true);
// บันทึกการนำเสนอที่แก้ไขแล้ว
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [BasePortionFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)