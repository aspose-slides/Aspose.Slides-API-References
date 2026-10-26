---
title: set_SpellCheck()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดค่าที่บ่งบอกว่าการตรวจสอบการสะกดถูกเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าพื้นฐานคือ false.
type: docs
weight: 612
url: /th/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) เมธอด


กำหนดค่าที่บ่งบอกว่าเปิดใช้งานการตรวจสอบการสะกดสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ถูกตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบของข้อความจะถูกระงับ เมื่อถูกตั้งค่าเป็น true จะอนุญาตให้ตรวจสอบการสะกด ค่าพื้นฐานคือ **false**.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## หมายเหตุ


ตัวอย่างต่อไปนี้แสดงการเปิดใช้งานแฟล็ก SpellCheck ก่อนบันทึกงานนำเสนอ: 
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

* คลาส [IBasePortionFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)