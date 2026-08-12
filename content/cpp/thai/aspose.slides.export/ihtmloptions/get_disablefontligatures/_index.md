---  
title: get_DisableFontLigatures()  
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++  
description: รับค่าที่บ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเทอเจอร์หรือไม่ เมื่อกำหนดเป็น true ลิเทอเจอร์จะถูกปิดการใช้งานในผลลัพธ์ที่แสดง โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น false.  
type: docs  
weight: 183  
url: /th/aspose.slides.export/ihtmloptions/get_disablefontligatures/  
---
## IHtmlOptions::get_DisableFontLigatures() วิธีการ

รับค่าที่บ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเทอเจอร์หรือไม่ เมื่อกำหนดเป็น **true** ลิเทอเจอร์จะถูกปิดการใช้งานในผลลัพธ์ที่แสดง โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // ปิดการใช้งานลิเทอเจอร์ในการเรนเดอร์ข้อความ

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## ดูเพิ่มเติม

* คลาส [IHtmlOptions](../)
* เนมส페ซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)