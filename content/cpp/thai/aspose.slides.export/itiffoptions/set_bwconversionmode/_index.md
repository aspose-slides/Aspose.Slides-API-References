---
title: set_BwConversionMode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ระบุอัลกอริทึมสำหรับการแปลงภาพสีเป็นภาพขาว-ดำ. ตัวเลือกนี้จะถูกนำไปใช้เฉพาะเมื่อ ITiffOptions::get_CompressionType() ถูกตั้งค่าเป็น TiffCompressionTypes::CCITT4 หรือ TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. ค่าเริ่มต้นคือ BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /th/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) เมธอด

ระบุอัลกอริทึมสำหรับการแปลงภาพสีเป็นภาพขาว-ดำ. ตัวเลือกนี้จะถูกนำไปใช้เฉพาะเมื่อ [ITiffOptions::get_CompressionType()](../get_compressiontype/) ถูกตั้งค่าเป็น [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) หรือ [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). ค่าเริ่มต้นคือ [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการตั้งค่าอัลกอริทึมการแปลงเป็น Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## ดูเพิ่มเติม

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* คลาส [ITiffOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)