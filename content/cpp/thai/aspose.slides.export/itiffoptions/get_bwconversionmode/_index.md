---
title: get_BwConversionMode()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "ระบุอัลกอริทึมสำหรับแปลงภาพสีเป็นภาพสีดำและสีขาว ตัวเลือกนี้จะถูกนำไปใช้เฉพาะเมื่อ ITiffOptions::get_CompressionType() ถูกตั้งค่าเป็น TiffCompressionTypes::CCITT4 หรือ TiffCompressionTypes::CCITT3 อ่าน BlackWhiteConversionMode ค่าเริ่มต้นคือ BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /th/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() เมธอด

กำหนดอัลกอริทึมสำหรับแปลงภาพสีเป็นภาพสีดำและสีขาว ตัวเลือกนี้จะทำงานเฉพาะเมื่อ [ITiffOptions::get_CompressionType()](../get_compressiontype/) ถูกตั้งค่าเป็น [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) หรือ [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) อ่าน [BlackWhiteConversionMode](../../blackwhiteconversionmode/) ค่าเริ่มต้นคือ [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
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
* คลาส [ITiffOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)