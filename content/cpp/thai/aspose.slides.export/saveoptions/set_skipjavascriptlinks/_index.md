---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียกใช้ JavaScript หรือไม่เมื่อบันทึกการนำเสนอ เขียนเป็น bool ค่าเริ่มต้นคือ false.
type: docs
weight: 118
url: /th/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) เมธอด

ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียกใช้ JavaScript หรือไม่เมื่อบันทึกการนำเสนอ เขียนเป็น **bool** ค่าเริ่มต้นคือ **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## หมายเหตุ

เมื่อคุณสมบัตินี้ถูกตั้งค่าเป็น **true** ไฮเปอร์ลิงก์ที่มีการเรียกใช้ JavaScript จะถูกละเว้นขณะบันทึก

เมื่อคุณสมบัตินี้ถูกตั้งค่าเป็น **false** ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก

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