---
title: set_BwConversionMode()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: "Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato volba bude použita pouze pokud je ITiffOptions::get_CompressionType() nastaven na TiffCompressionTypes::CCITT4 nebo TiffCompressionTypes::CCITT3 Zapsat BlackWhiteConversionMode. Výchozí hodnota je BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /cs/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metoda

Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato možnost bude použita pouze pokud je [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) nastaven na [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) nebo [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Zapsat [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Výchozí hodnota je [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
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
* Třída [TiffOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)