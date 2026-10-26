---
title: best_images_compression_ratio property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/ipdfoptions/best_images_compression_ratio/
weight: 50
---
## best_images_compression_ratio propriété
Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée 
            automatiquement. Si elle est réglée sur **bool**.true, pour chaque image de la présentation l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant. 
            La sélection du meilleur ratio de compression d'image est coûteuse en calcul et nécessite une quantité supplémentaire de RAM, et cette option est **bool**.false par défaut.

### Remarques

Par défaut, **bool**.false.

### Définition:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```

### Voir aussi
* classe [`IPdfOptions`](/slides/python-net/fr/aspose.slides.export/ipdfoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)