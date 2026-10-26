---
title: set_SaveMetafilesAsPng()
second_title: Référence API Aspose.Slides pour C++
description: True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Écrire bool.
type: docs
weight: 339
url: /fr/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) méthode

True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Écrire **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Remarques

La valeur par défaut est **true**. Un document Pdf peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est défini sur true, alors l'image Metafile source est convertie au format Png et enregistrée dans le Pdf en tant qu'image raster. Si SaveMetafilesAsPng est défini sur false, alors le Metafile source est converti en graphiques vectoriels Pdf. Chaque approche a des avantages et des inconvénients. Par exemple, si le Metafile est converti en PNG, une certaine perte de qualité peut survenir lors du redimensionnement du document résultant. Si le Metafile est converti en graphiques vectoriels Pdf, des problèmes de performances dans l'outil de visualisation Pdf sont possibles. 

## Voir aussi

* Classe [PdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)