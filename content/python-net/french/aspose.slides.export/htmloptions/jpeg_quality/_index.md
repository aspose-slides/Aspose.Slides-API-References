---
title: jpeg_quality property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/htmloptions/jpeg_quality/
weight: 90
---
## jpeg_quality propriété
Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF.
            Lecture/écriture **int**.


### Remarques

A un effet uniquement lorsqu'un document contient des images JPEG.


Utilisez cette propriété pour obtenir ou définir la qualité des images dans un document lors de l'enregistrement au format PDF.
            La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais une compression maximale et 100 signifie la meilleure qualité mais une compression minimale.


La valeur par défaut est **95** .

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
* classe [`HtmlOptions`](/slides/python-net/fr/aspose.slides.export/htmloptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)