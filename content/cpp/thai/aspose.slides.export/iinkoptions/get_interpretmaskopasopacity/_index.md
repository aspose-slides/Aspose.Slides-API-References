---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ใช้การดำเนินการ ROP หรือความทึบสำหรับการเรนเดอร์แปรง.
type: docs
weight: 27
url: /th/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() เมธอด


ใช้การดำเนินการ ROP หรือความทึบสำหรับการเรนเดอร์แปรง.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
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

* คลาส [IInkOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)