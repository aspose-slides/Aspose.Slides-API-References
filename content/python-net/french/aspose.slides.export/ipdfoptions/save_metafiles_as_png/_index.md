---
title: save_metafiles_as_png property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png propriété
True pour convertir tous les métafichiers utilisés dans une présentation en images PNG.
            Lecture/écriture **bool**.


### Remarques

La valeur par défaut est **true** .
            Le document Pdf peut contenir des graphiques vectoriels et des images raster. 
            Si SaveMetafilesAsPng est défini sur true alors l'image Metafile source est convertie au format Png et enregistrée dans le Pdf comme une image raster. Si SaveMetafilesAsPng est défini sur false alors le Metafile source est converti en graphiques vectoriels Pdf. Chaque approche a des avantages et des inconvénients. Par exemple, si Metafile est converti en PNG, alors une perte de qualité est possible lors du redimensionnement du document résultant. Si Metafile est converti en graphiques vectoriels Pdf, alors des problèmes de performances dans l'outil de visualisation Pdf sont possibles.

### Définition:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```


### Voir aussi
* classe [`IPdfOptions`](/slides/python-net/fr/aspose.slides.export/ipdfoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)