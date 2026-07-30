---
title: set_BwConversionMode()
second_title: Aspose.Slides pro C++ API Reference
description: "Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato volba bude použita pouze pokud je ITiffOptions::get_CompressionType() nastaven na TiffCompressionTypes::CCITT4 nebo TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Výchozí hodnota je BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /cs/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metoda

Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato volba bude použita pouze pokud je [ITiffOptions::get_CompressionType()](../get_compressiontype/) nastaven na [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) nebo [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Výchozí hodnota je [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
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
* Class [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)