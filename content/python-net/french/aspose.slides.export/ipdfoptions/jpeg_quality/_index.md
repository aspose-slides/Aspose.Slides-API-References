---
title: jpeg_quality property
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## jpeg_quality propriété
Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF.
            Lecture/écriture **int**.

### Remarques

N'a d'effet que lorsqu'un document contient des images JPEG.

Utilisez cette propriété pour obtenir ou définir la qualité des images à l'intérieur d'un document lors de l'enregistrement au format PDF.
            La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale.

La valeur par défaut est **100** .

### Définition:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```

### Voir aussi
* classe [`IPdfOptions`](/slides/python-net/fr/aspose.slides.export/ipdfoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)