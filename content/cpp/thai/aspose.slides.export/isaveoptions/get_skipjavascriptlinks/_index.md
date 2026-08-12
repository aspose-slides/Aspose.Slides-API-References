---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ. อ่าน bool. ค่าเริ่มต้นคือ false.
type: docs
weight: 105
url: /th/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() เมธอด


ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อตอนบันทึกการนำเสนอ. อ่าน **bool**. ค่าเริ่มต้นคือ **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## หมายเหตุ


เมื่อคุณสมบัตินี้ตั้งค่าเป็น **true**, ไฮเปอร์ลิงก์ที่มีการเรียก JavaScript จะถูกละเว้นขณะบันทึก.

เมื่อคุณสมบัตินี้ตั้งค่าเป็น **false**, ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก.

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