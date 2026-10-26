---
title: set_SkipJavaScriptLinks()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ เขียนเป็น bool. ค่าตั้งต้นคือ false.
type: docs
weight: 118
url: /th/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) เมธอด


ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ. เขียน **bool**. ค่าตั้งต้นคือ **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## หมายเหตุ


เมื่อคุณสมบัตินี้ถูกตั้งค่าเป็น **true**, ไฮเปอร์ลิงก์ที่มีการเรียก JavaScript จะถูกละเว้นขณะบันทึก.

เมื่อคุณสมบัตินี้ถูกตั้งค่าเป็น **false**, ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก.

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## ดูเพิ่มเติม

* คลาส [ISaveOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)