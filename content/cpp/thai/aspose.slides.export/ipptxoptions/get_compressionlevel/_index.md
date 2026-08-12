---
title: get_CompressionLevel()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ ค่าเริ่มต้นคือ CompressionLevel::Level6."
type: docs
weight: 79
url: /th/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() เมธอด

ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ ค่าเริ่มต้นคือ [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## หมายเหตุ

ระดับการบีบอัดที่สูงกว่าจะทำให้ไฟล์มีขนาดเล็กลงแต่ต้องใช้เวลาประมวลผลมากขึ้น อัตราการบีบอัดจริงขึ้นอยู่กับเนื้อหาของงานนำเสนอ.

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
* ไลบรารี [Aspose.Slides](../../../)