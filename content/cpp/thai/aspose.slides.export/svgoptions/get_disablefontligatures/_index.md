---
title: get_DisableFontLigatures()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์ เมื่อกำหนดเป็น true ลิเกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้น คุณสมบัตินี้ถูกตั้งค่าเป็น false.
type: docs
weight: 326
url: /th/aspose.slides.export/svgoptions/get_disablefontligatures/
---
## SVGOptions::get_DisableFontLigatures() เมธอด

รับค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์ เมื่อกำหนดเป็น **true** ลิเกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้น คุณสมบัตินี้ถูกตั้งค่าเป็น **false**.

```cpp
bool Aspose::Slides::Export::SVGOptions::get_DisableFontLigatures() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // ปิดการใช้ลิเกเจอร์ในการแสดงผลข้อความ

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## ดูเพิ่มเติม

* คลาส [SVGOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)