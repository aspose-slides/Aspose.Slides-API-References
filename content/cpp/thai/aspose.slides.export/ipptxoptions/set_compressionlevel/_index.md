---
title: set_CompressionLevel()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารการนำเสนอ ค่าเริ่มต้นคือ CompressionLevel::Level6."
type: docs
weight: 92
url: /th/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) เมธอด


ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารการนำเสนอ ค่าเริ่มต้นคือ [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## หมายเหตุ


ระดับการบีบอัดที่สูงกว่าจะทำให้ไฟล์มีขนาดเล็กลง แต่ต้องใช้เวลาประมวลผลมากขึ้น อัตราการบีบอัดจริงขึ้นอยู่กับเนื้อหาของการนำเสนอ. 

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## ดูเพิ่มเติม

* Enum [CompressionLevel](../../compressionlevel/)
* คลาส [IPptxOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)