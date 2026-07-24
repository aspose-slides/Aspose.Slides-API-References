---
title: set_BwConversionMode()
second_title: Aspose.Slides for C++ API Referansı
description: "Renkli bir görüntüyü siyah beyaz bir görüntüye dönüştürmek için algoritmayı belirtir. Bu seçenek yalnızca ITiffOptions::get_CompressionType() TiffCompressionTypes::CCITT4 veya TiffCompressionTypes::CCITT3 Yaz BlackWhiteConversionMode olarak ayarlandığında uygulanır. Varsayılan BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /tr/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) method


Renkli bir görüntüyü siyah beyaz bir görüntüye dönüştürmek için algoritmayı belirler. Bu seçenek yalnızca [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ya da [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Yaz [BlackWhiteConversionMode](../../blackwhiteconversionmode/) olarak ayarlandığında uygulanır. Varsayılan [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## Açıklamalar


Aşağıdaki örnek, dönüştürme algoritmasını Dithering olarak ayarlamayı gösterir. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## İlgili

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Sınıf [TiffOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)