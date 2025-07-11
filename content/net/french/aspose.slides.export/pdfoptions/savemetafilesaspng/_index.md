---
title: SaveMetafilesAsPng
second_title: Aspose.Sildes pour .NET API Référence
description: Vrai pour convertir tous les mét fichiers utilisés dans une présentation en images PNG. Lecture/écriture Booléen.
type: docs
weight: 160
url: /fr/aspose.slides.export/pdfoptions/savemetafilesaspng/
---

## PdfOptions.SaveMetafilesAsPng propriété

Vrai pour convertir tous les mét fichiers utilisés dans une présentation en images PNG. Lecture/écriture Booléen.

```csharp
public bool SaveMetafilesAsPng { get; set; }
```

### Remarques

La valeur par défaut est **vraie**. Un document Pdf peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est défini sur vrai, alors l'image Métafile source est convertie au format Png et enregistrée dans le Pdf en tant qu'image raster. Si SaveMetafilesAsPng est défini sur faux, alors le Métafile source est converti en graphiques vectoriels Pdf. Chaque approche a ses avantages et inconvénients. Par exemple, si le Métafile est converti en PNG, alors une perte de qualité peut se produire lors du redimensionnement du document résultant. Si le Métafile est converti en graphiques vectoriels Pdf, des problèmes de performance dans l'outil de visualisation Pdf sont possibles.

### Voir aussi

* classe [PdfOptions](../../pdfoptions)
* namespace [Aspose.Slides.Export](../../pdfoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->