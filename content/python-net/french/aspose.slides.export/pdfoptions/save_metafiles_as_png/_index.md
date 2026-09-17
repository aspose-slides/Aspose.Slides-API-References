---
title: save_metafiles_as_png property
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png propriété
True pour convertir tous les métafichiers utilisés dans une présentation en images PNG.
            Lecture/écriture **bool**.


### Remarques

Par défaut, la valeur est **true**.
            Un document Pdf peut contenir des graphiques vectoriels et des images raster. 
            Si SaveMetafilesAsPng est défini sur true alors le Metafile source 
            image est convertie au format Png et enregistrée dans le Pdf en tant qu'image raster 
            image. Si SaveMetafilesAsPng est défini sur false alors le Metafile source 
            est converti en graphiques vectoriels Pdf. Chaque approche présente des avantages 
            et des inconvénients. Par exemple, si Metafile est converti en PNG, 
            une certaine perte de qualité est possible lors du redimensionnement du 
            document résultant. Si Metafile est converti en graphiques vectoriels Pdf, 
            des problèmes de performance dans l'outil de visualisation du Pdf sont possibles.

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
* classe [`PdfOptions`](/slides/python-net/fr/aspose.slides.export/pdfoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)