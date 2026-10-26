---
title: set_SaveMetafilesAsPng()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Écrire bool.
type: docs
weight: 300
url: /fr/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) méthode

Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Écrire **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Remarques

Par défaut, c'est **true**. Le document Pdf peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est défini sur true, alors l'image Metafile source est convertie au format Png et enregistrée dans le Pdf en tant qu'image raster. Si SaveMetafilesAsPng est défini sur false, alors le Metafile source est converti en graphiques vectoriels Pdf. Chaque approche a des avantages et des inconvénients. Par exemple, si le Metafile est converti en PNG, une perte de qualité peut survenir lors du redimensionnement du document résultant. Si le Metafile est converti en graphiques vectoriels Pdf, des problèmes de performance dans l'outil de visualisation Pdf sont possibles.

## Voir aussi

* Classe [IPdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)