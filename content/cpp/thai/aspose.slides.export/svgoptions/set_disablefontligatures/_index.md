---
title: set_DisableFontLigatures()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงโดยไม่ใช้ลีแกตูร เมื่อกำหนดเป็น true ค่าลีแกตูรจะถูกปิดการใช้งานในผลลัพธ์ที่แสดงออกมา ค่าเริ่มต้นของคุณสมบัตินี้คือ false.
type: docs
weight: 339
url: /th/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) เมธอด

กำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงโดยไม่ใช้ลีแกตูร หากตั้งค่าเป็น **true** จะทำให้ลีแกตูรถูกปิดการใช้งานในผลลัพธ์ที่แสดงออกมา ค่าเริ่มต้นของคุณสมบัตินี้คือ **false**.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // ปิดการใช้ลีแกตูรในการแสดงข้อความ

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## ดูเพิ่มเติม

* คลาส [SVGOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)