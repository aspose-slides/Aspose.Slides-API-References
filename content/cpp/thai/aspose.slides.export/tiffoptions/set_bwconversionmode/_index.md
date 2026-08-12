---
title: set_BwConversionMode()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ระบุอัลกอริธึมสำหรับการแปลงภาพสีเป็นภาพขาวดำ ตัวเลือกนี้จะใช้ก็ต่อเมื่อ ITiffOptions::get_CompressionType() ถูกตั้งค่าเป็น TiffCompressionTypes::CCITT4 หรือ TiffCompressionTypes::CCITT3 เขียน BlackWhiteConversionMode ค่าเริ่มต้นคือ BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /th/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) เมธอด

ระบุอัลกอริธึมสำหรับการแปลงภาพสีเป็นภาพขาวดำ ตัวเลือกนี้จะใช้ก็ต่อเมื่อ [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) ถูกตั้งค่าเป็น [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) หรือ [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) เขียน [BlackWhiteConversionMode](../../blackwhiteconversionmode/) ค่าเริ่มต้นคือ [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าอัลกอริธึมการแปลงเป็น Dithering.
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
* ไลบรารี [Aspose.Slides](../../../)