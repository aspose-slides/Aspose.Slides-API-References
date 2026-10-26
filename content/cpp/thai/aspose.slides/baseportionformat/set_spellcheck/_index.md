---
title: set_SpellCheck()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดค่าซึ่งบ่งบอกว่าการตรวจสอบการสะกดคำเปิดใช้งานสำหรับส่วนข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกปิดใช้งาน เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าเริ่มต้นคือ false.
type: docs
weight: 612
url: /th/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) เมธอด

ตั้งค่าค่าซึ่งระบุว่าการตรวจสอบการสะกดคำถูกเปิดใช้งานสำหรับส่วนข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกปิดใช้งาน เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะถูกเปิดใช้งาน ค่าเริ่มต้นคือ **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้สาธิตการเปิดใช้งานแฟล็ก SpellCheck ก่อนบันทึกงานนำเสนอ:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [BasePortionFormat](../)
* เนมส페ซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)