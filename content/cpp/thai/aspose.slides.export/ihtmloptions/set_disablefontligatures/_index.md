---
title: set_DisableFontLigatures()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: กำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ ligatures. เมื่อกำหนดเป็น true, ligatures จะถูกปิดในผลลัพธ์ที่แสดง. โดยค่าเริ่มต้น, คุณสมบัตินี้จะถูกตั้งเป็น false.
type: docs
weight: 196
url: /th/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) เมธอด


กำหนดค่าที่ระบุว่าข้อความถูกแสดงโดยไม่ใช้ ligatures. เมื่อกำหนดเป็น **true**, ligatures จะถูกปิดในผลลัพธ์ที่แสดง. โดยค่าเริ่มต้น, คุณสมบัตินี้จะถูกตั้งเป็น **false**.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // ปิด ligatures ในการแสดงผลข้อความ

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## ดูเพิ่มเติม

* คลาส [IHtmlOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)