---
title: set_InterpretMaskOpAsOpacity()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ใช้การดำเนินการ ROP หรือความทึบแสงสำหรับการเรนเดอร์แปรง.
type: docs
weight: 40
url: /th/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) เมธอด

ใช้การดำเนินการ ROP หรือความทึบแสงสำหรับการเรนเดอร์แปรง.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
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