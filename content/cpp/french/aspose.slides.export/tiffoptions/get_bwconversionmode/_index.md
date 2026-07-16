---
title: get_BwConversionMode()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. Cette option sera appliquée uniquement si ITiffOptions::get_CompressionType() est défini sur TiffCompressionTypes::CCITT4 ou TiffCompressionTypes::CCITT3 Lire BlackWhiteConversionMode. La valeur par défaut est BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /fr/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() méthode

Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. Cette option sera appliquée uniquement si [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) est défini sur [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ou [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Lire [BlackWhiteConversionMode](../../blackwhiteconversionmode/). La valeur par défaut est [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## Remarques

L'exemple suivant montre comment définir l'algorithme de conversion sur Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Voir aussi

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)