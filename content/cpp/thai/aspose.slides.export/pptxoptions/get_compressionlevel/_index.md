---
title: get_CompressionLevel()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารการนำเสนอ ค่าเริ่มต้นคือ CompressionLevel::Level6."
type: docs
weight: 79
url: /th/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() เมธอด


กำหนดระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารการนำเสนอ ค่าเริ่มต้นคือ [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## หมายเหตุ


ระดับการบีบอัดที่สูงกว่าจะทำให้ไฟล์มีขนาดเล็กลงแต่ต้องใช้เวลาประมวลผลมากขึ้น อัตราการบีบอัดจริงขึ้นอยู่กับเนื้อหาของการนำเสนอ. 

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## ดูเพิ่มเติม

* Enum [CompressionLevel](../../compressionlevel/)
* คลาส [PptxOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)