---
title: get_BwConversionMode()
second_title: Aspose.Slides pro C++ API Reference
description: "Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato volba bude použita pouze, pokud ITiffOptions::get_CompressionType() je nastaveno na TiffCompressionTypes::CCITT4 nebo TiffCompressionTypes::CCITT3 Read BlackWhiteConversionMode. Výchozí hodnota je BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /cs/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() metoda


Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato volba bude použita pouze, pokud [ITiffOptions::get_CompressionType()](../get_compressiontype/) je nastaveno na [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) nebo [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Přečtěte si [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Výchozí hodnota je [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## Poznámky


Následující příklad ukazuje, jak nastavit algoritmus převodu na Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Viz také

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Třída [ITiffOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)