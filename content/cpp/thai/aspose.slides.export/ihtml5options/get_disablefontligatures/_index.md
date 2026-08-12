---
title: get_DisableFontLigatures()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับค่าที่บ่งชี้ว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิกเชอร์หรือไม่ เมื่อกำหนดเป็น true ลิกเชอร์จะถูกปิดการใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้น คุณสมบัตินี้จะถูกตั้งค่าเป็น false.
type: docs
weight: 131
url: /th/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() เมธอด

ได้รับค่าที่บ่งชี้ว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิกเชอร์หรือไม่ เมื่อกำหนดเป็น **true** ลิกเชอร์จะถูกปิดการใช้งานในผลลัพธ์ที่แสดงโดยค่าเริ่มต้น คุณสมบัตินี้จะถูกตั้งค่าเป็น **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // ปิดการใช้ลิกเชอร์ในการเรนเดอร์ข้อความ

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## ดูเพิ่มเติม

* คลาส [IHtml5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)