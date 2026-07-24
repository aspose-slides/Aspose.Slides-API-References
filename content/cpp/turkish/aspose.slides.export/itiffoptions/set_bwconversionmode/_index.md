---
title: set_BwConversionMode()
second_title: Aspose.Slides for C++ API Referansı
description: "Renkli bir görüntüyü siyah beyaz bir görüntüye dönüştürme algoritmasını belirtir. Bu seçenek yalnızca ITiffOptions::get_CompressionType() TiffCompressionTypes::CCITT4 veya TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode olarak ayarlandığında uygulanır. Varsayılan BlackWhiteConversionMode::Default'tir."
type: docs
weight: 196
url: /tr/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metot

Renkli bir görüntüyü siyah beyaz bir görüntüye dönüştürme algoritmasını belirtir. Bu seçenek yalnızca [ITiffOptions::get_CompressionType()](../get_compressiontype/) [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) veya [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) olarak ayarlandığında uygulanır. Varsayılan [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## Açıklamalar

Aşağıdaki örnek, dönüşüm algoritmasını Dithering olarak ayarlamayı gösterir.

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
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)