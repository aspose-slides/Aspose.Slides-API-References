---
title: set_BwConversionMode()
second_title: Référence API Aspose.Slides pour C++
description: "Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. Cette option ne sera appliquée que si ITiffOptions::get_CompressionType() est défini sur TiffCompressionTypes::CCITT4 ou TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. La valeur par défaut est BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /fr/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) méthode

Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. Cette option ne sera appliquée que si [ITiffOptions::get_CompressionType()](../get_compressiontype/) est défini sur [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ou [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). La valeur par défaut est [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
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
* Class [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)