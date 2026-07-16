---
title: get_SaveMetafilesAsPng()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lire bool.
type: docs
weight: 287
url: /fr/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() méthode

True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lire **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Remarques

La valeur par défaut est **true**. Un document Pdf peut contenir des graphiques vectoriels et des images matricielles. Si SaveMetafilesAsPng est défini sur true, alors l'image Metafile source est convertie au format Png et enregistrée dans le Pdf en tant qu'image matricielle. Si SaveMetafilesAsPng est défini sur false, alors la Metafile source est convertie en graphiques vectoriels Pdf. Chaque approche présente des avantages et des inconvénients. Par exemple, si la Metafile est convertie en PNG, une certaine perte de qualité peut survenir lors du redimensionnement du document résultant. Si la Metafile est convertie en graphiques vectoriels Pdf, des problèmes de performance dans l'outil de visualisation du Pdf peuvent survenir. 
## Voir aussi

* Classe [IPdfOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)