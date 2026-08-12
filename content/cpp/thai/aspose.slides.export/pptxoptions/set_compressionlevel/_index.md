---
title: set_CompressionLevel()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ ค่าเริ่มต้นคือ CompressionLevel::Level6."
type: docs
weight: 92
url: /th/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) เมธอด


ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ ค่าเริ่มต้นคือ [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## หมายเหตุ


ระดับการบีบอัดที่สูงกว่าจะทำให้ไฟล์มีขนาดเล็กลง แต่ต้องใช้เวลาในการประมวลผลมากขึ้น อัตราส่วนการบีบอัดจริงขึ้นอยู่กับเนื้อหาของงานนำเสนอ. 

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