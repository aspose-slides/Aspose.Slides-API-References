---
title: get_DisableFontLigatures()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: รับค่าสำหรับบ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์หรือไม่ เมื่อกำหนดเป็น true, ลิแกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ถูกตั้งเป็น false.
type: docs
weight: 131
url: /th/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() เมธอด

รับค่าสำหรับบ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์หรือไม่ เมื่อกำหนดเป็น **true**, ลิแกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ถูกตั้งเป็น **false**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // ปิดการใช้ลิแกเจอร์ในกระบวนการเรนเดอร์ข้อความ

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## ดูเพิ่มเติม

* คลาส [Html5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)