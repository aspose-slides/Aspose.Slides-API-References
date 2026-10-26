---
title: get_DisableFontLigatures()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับค่าที่บ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์ เมื่อกำหนดเป็น true ลิเกเจอร์จะถูกปิดในผลลัพธ์ที่แสดงผล โดยค่าเริ่มต้น คุณสมบัตินี้ตั้งค่าเป็น false.
type: docs
weight: 92
url: /th/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() วิธีการ


รับค่าแสดงว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์ เมื่อกำหนดเป็น **true** ลิเกเจอร์จะถูกปิดในผลลัพธ์ที่แสดงผล โดยค่าเริ่มต้น คุณสมบัตินี้ตั้งค่าเป็น **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // ปิดลิเกเจอร์ในการเรนเดอร์ข้อความ

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## ดูเพิ่มเติม

* คลาส [HtmlOptions](../)
* เนมส페ซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)