---
title: set_BwConversionMode()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. Cette option ne sera appliquée que si ITiffOptions::get_CompressionType() est définie sur TiffCompressionTypes::CCITT4 ou TiffCompressionTypes::CCITT3 Écrire BlackWhiteConversionMode. La valeur par défaut est BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /fr/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) méthode

Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. Cette option ne sera appliquée que si [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) est définie sur [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ou [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). La valeur par défaut est [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
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
* Classe [TiffOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)