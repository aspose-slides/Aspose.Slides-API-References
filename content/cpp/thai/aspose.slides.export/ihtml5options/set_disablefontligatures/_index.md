---
title: set_DisableFontLigatures()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: ตั้งค่าค่าที่บ่งบอกว่าข้อความจะถูกแสดงโดยไม่ใช้ไลกเจอร์ เมื่อกำหนดเป็น true ไลกเจอร์จะถูกปิดการทำงานในผลลัพธ์ที่แสดง โดยค่าเริ่มต้นคุณสมบัตินี้จะถูกตั้งค่าเป็น false.
type: docs
weight: 144
url: /th/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) เมธอด

ตั้งค่าค่าที่ระบุว่าข้อความจะถูกแสดงโดยไม่ใช้ไลกเจอร์ เมื่อกำหนดเป็น **true** ไลกเจอร์จะถูกปิดการทำงานในผลลัพธ์ที่แสดง โดยค่าเริ่มต้นคุณสมบัตินี้จะถูกตั้งค่าเป็น **false**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // ปิดการใช้ไลกเจอร์ในการเรนเดอร์ข้อความ

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## ดูเพิ่มเติม

* คลาส [IHtml5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)