---
title: get_SpellCheck()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: รับค่าที่บ่งบอกว่าการตรวจสอบการสะกดคำถูกเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าเริ่มต้นคือ false.
type: docs
weight: 599
url: /th/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() เมธอด

รับค่าที่บ่งบอกว่าการตรวจสอบการสะกดคำถูกเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าเริ่มต้นคือ **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงการเปิดใช้แฟล็อก SpellCheck ก่อนบันทึกการนำเสนอ: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// เข้าถึงส่วนข้อความแรกภายในรูปร่างแรกบนสไลด์แรก
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// เปิดการตรวจสอบการสะกดสำหรับส่วนข้อความนี้
portion->get_PortionFormat()->set_SpellCheck(true);
// บันทึกการนำเสนอที่แก้ไขแล้ว
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IBasePortionFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)