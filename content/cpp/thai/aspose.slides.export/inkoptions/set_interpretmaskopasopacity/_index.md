---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ใช้การดำเนินการ ROP หรือความทึบแสงเพื่อเรนเดอร์แปรง.
type: docs
weight: 40
url: /th/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) เมธอด

ใช้การดำเนินการ ROP หรือความทึบแสงสำหรับเรนเดอร์แปรง.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## หมายเหตุ

ค่าเริ่มต้นคือ true.

ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าโดยใช้ ROP สำหรับการส่งออก [Ink](../../../aspose.slides.ink/) องค์ประกอบ:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## ดูเพิ่มเติม

* คลาส [InkOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)