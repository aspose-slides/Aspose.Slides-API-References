---
title: set_DisableFontLigatures()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตั้งค่าค่าที่บ่งชี้ว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิการเจอร์ เมื่อกำหนดเป็น true ลิการเจอร์จะถูกปิดการใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ถูกตั้งค่าเป็น false.
type: docs
weight: 105
url: /th/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) เมธอด


ตั้งค่าค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิการเจอร์ เมื่อกำหนดเป็น **true** ลิการเจอร์จะถูกปิดการใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ถูกตั้งค่าเป็น **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // ปิดการใช้ลิการเจอร์ในการเรนเดอร์ข้อความ

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## ดูเพิ่มเติม

* คลาส [HtmlOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)