---
title: get_BwConversionMode()
second_title: Aspose.Slides için C++ API Referansı
description: "Renkli bir görüntüyü siyah ve beyaz bir görüntüye dönüştürmek için algoritmayı belirler. Bu seçenek yalnızca ITiffOptions::get_CompressionType() TiffCompressionTypes::CCITT4 veya TiffCompressionTypes::CCITT3 Read BlackWhiteConversionMode ayarlandığında uygulanır. Varsayılan BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /tr/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() metodu

Renkli bir görüntüyü siyah-beyaz bir görüntüye dönüştürmek için algoritmayı belirtir. Bu seçenek yalnızca [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) veya [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Read [BlackWhiteConversionMode](../../blackwhiteconversionmode/) ayarlandığında uygulanır. Varsayılan [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## Açıklamalar

Aşağıdaki örnek dönüşüm algoritmasını Dithering olarak ayarlamayı gösterir.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## İlgili

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)