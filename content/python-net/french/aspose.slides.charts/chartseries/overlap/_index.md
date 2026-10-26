---
title: overlap property
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## propriété overlap
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent.
            C'est une projection de la propriété appropriée dans le groupe de séries parent, et cette propriété est donc en lecture seule.
            Pour modifier la valeur, utilisez la propriété en lecture/écriture **ParentSeriesGroup.Overlap**.
            Lecture seule **int**.

### Remarques

Overlap spécifie le degré de chevauchement ou d'espacement entre les barres et les colonnes en pourcentage de leur largeur :
            - -100%: Espacement maximal (les barres sont complètement séparées).
            - 0%: Les barres sont placées côte à côte sans chevauchement ni espacement.
            - 100%: Chevauchement maximal (les barres se chevauchent complètement).
            Il s'agit d'une projection de la propriété **ParentSeriesGroup.Overlap**.

### Définition:
```python
@property
def overlap(self):
    ...
```


### Voir aussi
* classe [`ChartSeries`](/slides/python-net/fr/aspose.slides.charts/chartseries)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)