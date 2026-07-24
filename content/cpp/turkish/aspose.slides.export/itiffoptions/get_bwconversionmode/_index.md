---
title: get_BwConversionMode()
second_title: Aspose.Slides için C++ API Referansı
description: "Renkli bir resmi siyah beyaz bir resme dönüştürmek için kullanılan algoritmayı belirtir. Bu seçenek yalnızca ITiffOptions::get_CompressionType() TiffCompressionTypes::CCITT4 veya TiffCompressionTypes::CCITT3 olarak ayarlandığında uygulanır. Okuyun BlackWhiteConversionMode. Varsayılan BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /tr/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() metod


Renkli bir resmi siyah beyaz bir resme dönüştürmek için kullanılan algoritmayı belirtir. Bu seçenek yalnızca [ITiffOptions::get_CompressionType()](../get_compressiontype/) [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) veya [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Okuma [BlackWhiteConversionMode](../../blackwhiteconversionmode/) ayarlandığında uygulanır. Varsayılan [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/)'dir.

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## Açıklamalar


Aşağıdaki örnek, dönüşüm algoritmasını Dithering olarak nasıl ayarlayacağınızı gösterir.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Ayrıca

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Sınıf [ITiffOptions](../)
* İsim Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)