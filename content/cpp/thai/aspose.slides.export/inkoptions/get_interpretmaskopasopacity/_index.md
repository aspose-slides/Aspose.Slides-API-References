---
title: get_InterpretMaskOpAsOpacity()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ใช้การทำงาน ROP หรือความทึบแสงสำหรับการเรนเดอร์แปรง.
type: docs
weight: 27
url: /th/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() เมธอด

ใช้การทำงาน ROP หรือความทึบแสงสำหรับการเรนเดอร์แปรง.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## หมายเหตุ

ค่าเริ่มต้นคือ true. 

ตัวอย่างต่อไปแสดงวิธีตั้งค่าโดยใช้ ROP สำหรับการส่งออกองค์ประกอบ [Ink](../../../aspose.slides.ink/): 
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