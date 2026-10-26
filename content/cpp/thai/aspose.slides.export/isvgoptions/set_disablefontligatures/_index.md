---
title: set_DisableFontLigatures()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: กำหนดค่าที่บ่งชี้ว่าข้อความจะถูกแสดงโดยไม่ใช้ลิเกเจอร์ เมื่อกำหนดเป็น true, ลิเกเจอร์จะถูกปิดใช้งานในผลลัพธ์ที่แสดงออก โดยค่าเริ่มต้นคุณสมบัตินี้ถูกตั้งค่าเป็น false.
type: docs
weight: 339
url: /th/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISSVGOptions::set_DisableFontLigatures(bool) เมธอด


กำหนดค่าที่บ่งชี้ว่าข้อความจะถูกแสดงโดยไม่ใช้ลิเกเจอร์ เมื่อกำหนดเป็น **true**, ลิเกเจอร์จะถูกปิดใช้งานในผลลัพธ์ที่แสดงออก โดยค่าเริ่มต้นคุณสมบัตินี้ถูกตั้งค่าเป็น **false**.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // ปิดลิเกเจอร์ในการแสดงผลข้อความ

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## ดูเพิ่มเติม

* คลาส [ISVGOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)