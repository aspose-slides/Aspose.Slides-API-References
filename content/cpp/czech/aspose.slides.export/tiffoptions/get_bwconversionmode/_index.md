---
title: get_BwConversionMode()
second_title: Aspose.Slides pro C++ API Reference
description: "Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato možnost bude použita pouze pokud je ITiffOptions::get_CompressionType() nastaven na TiffCompressionTypes::CCITT4 nebo TiffCompressionTypes::CCITT3. Přečtěte BlackWhiteConversionMode. Výchozí hodnota je BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /cs/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() metoda


Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato možnost bude použita pouze pokud je [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) nastaven na [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) nebo [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/). Přečtěte [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Výchozí hodnota je [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
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

* Výčet [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Třída [TiffOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)