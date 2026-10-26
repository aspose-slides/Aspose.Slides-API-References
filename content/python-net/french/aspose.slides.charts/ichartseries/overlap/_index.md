---
title: overlap property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## overlap propriété
Spécifie combien les barres et les colonnes se chevauchent sur des graphiques 2-D, en pourcentage (de -100% à 100%). 
            Cette propriété ne concerne pas seulement cette série, mais toutes les séries du groupe de séries parent. 
            Il s'agit d'une projection de la propriété appropriée dans le groupe de séries parent, et cette propriété est donc en lecture seule.
            Pour modifier la valeur, utilisez la propriété ParentSeriesGroup.Overlap en lecture/écriture.
            Lecture seule **int**.

### Remarques

Overlap indique le degré de chevauchement ou d'espacement entre les barres et les colonnes en pourcentage de leur largeur:
            - -100%: Espacement maximal (les barres sont complètement séparées).
            - 0%: Les barres sont placées côte à côte sans chevauchement ni espacement.
            - 100%: Chevauchement maximal (les barres se chevauchent complètement).
            Il s'agit d'une projection de la propriété ParentSeriesGroup.Overlap.

### Définition:
```python
@property
def overlap(self):
    ...
```

### Voir également
* classe [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)