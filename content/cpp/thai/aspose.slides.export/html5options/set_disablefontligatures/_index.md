---
title: set_DisableFontLigatures()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิการ์จ เมื่อกำหนดเป็น true ลิการ์จจะถูกปิดการใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้จะถูกตั้งค่าเป็น false.
type: docs
weight: 144
url: /th/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) เมธอด


ตั้งค่าค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิการ์จ เมื่อกำหนดเป็น **true** ลิการ์จจะถูกปิดการใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้จะถูกตั้งค่าเป็น **false**.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // ปิดการใช้งานลิการ์จในการเรนเดอร์ข้อความ

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## ดูเพิ่มเติม

* คลาส [Html5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)