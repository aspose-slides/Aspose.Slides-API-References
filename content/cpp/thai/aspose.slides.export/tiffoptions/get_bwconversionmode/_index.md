---
title: get_BwConversionMode()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "ระบุอัลกอริทึมสำหรับการแปลงภาพสีเป็นภาพขาว-ดำ ตัวเลือกนี้จะใช้ได้เฉพาะเมื่อ ITiffOptions::get_CompressionType() ตั้งค่าเป็น TiffCompressionTypes::CCITT4 หรือ TiffCompressionTypes::CCITT3 อ่าน BlackWhiteConversionMode ค่าเริ่มต้นคือ BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /th/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() เมธอด

ระบุอัลกอริทึมสำหรับการแปลงภาพสีเป็นภาพขาว-ดำ ตัวเลือกนี้จะใช้ได้เฉพาะเมื่อ [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) ตั้งค่าเป็น [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) หรือ [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) อ่าน [BlackWhiteConversionMode](../../blackwhiteconversionmode/) ค่าเริ่มต้นคือ [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าอัลกอริทึมการแปลงเป็น Dithering.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## ดูเพิ่มเติม

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* คลาส [TiffOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)