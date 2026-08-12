---
title: get_DisableFontLigatures()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับค่าที่บ่งบอกว่าข้อความถูกแสดงโดยไม่ใช้ลิแกเชอร์หรือไม่ เมื่อกำหนดเป็น true ลิแกเชอร์จะถูกปิดการใช้งานในผลลัพธ์ที่แสดง โดยค่าเริ่มต้นคุณสมบัตินี้จะถูกตั้งค่าเป็น false.
type: docs
weight: 326
url: /th/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISVGOptions::get_DisableFontLigatures() เมธอด


รับค่าที่บ่งบอกว่าข้อความถูกแสดงโดยไม่ใช้ลิแกเชอร์หรือไม่ เมื่อกำหนดเป็น **true** ลิแกเชอร์จะถูกปิดการใช้งานในผลลัพธ์ที่แสดง โดยค่าเริ่มต้นคุณสมบัตินี้จะถูกตั้งค่าเป็น **false**.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## หมายเหตุ


ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // ปิดการใช้ลิแกเชอร์ในการแสดงข้อความ

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## ดูเพิ่มเติม

* คลาส [ISVGOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)