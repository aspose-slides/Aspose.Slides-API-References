---
title: get_SaveMetafilesAsPng()
second_title: Référence de l'API Aspose.Slides pour C++
description: True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lire bool.
type: docs
weight: 326
url: /fr/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() méthode


True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lire **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Remarques


Par défaut, la valeur est **true**. Pdf document peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est défini sur true alors l'image Metafile source est convertie au format Png et enregistrée dans le Pdf en tant qu'image raster. Si SaveMetafilesAsPng est défini sur false alors la Metafile source est convertie en graphiques vectoriels Pdf. Chaque approche a des avantages et des inconvénients. Par exemple, si la Metafile est convertie en PNG, alors une perte de qualité est possible lors du redimensionnement du document résultant. Si la Metafile est convertie en graphiques vectoriels Pdf, alors des problèmes de performances dans l'outil de visualisation Pdf sont possibles. 
## Voir aussi

* Classe [PdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)