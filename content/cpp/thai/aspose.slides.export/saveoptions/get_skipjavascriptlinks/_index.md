---
title: get_SkipJavaScriptLinks()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียกใช้ JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ อ่าน bool ค่าเริ่มต้นคือ false.
type: docs
weight: 105
url: /th/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() วิธีการ

ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียกใช้ JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ อ่าน **bool**. ค่าเริ่มต้นคือ **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## หมายเหตุ

เมื่อคุณสมบัตินี้ถูกตั้งค่าเป็น **true** ไฮเปอร์ลิงก์ที่มีการเรียกใช้ JavaScript จะถูกละเว้นขณะบันทึก

เมื่อคุณสมบัตินี้ถูกตั้งค่าเป็น **false** ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## ดูเพิ่มเติม

* คลาส [SaveOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)