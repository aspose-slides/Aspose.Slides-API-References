---
title: get_Overlap()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie le degré de chevauchement des barres et des colonnes sur les graphiques 2D, en pourcentage (de -100% à 100%). Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent. C'est une projection de la propriété appropriée dans le groupe de séries parent, et cette propriété est donc en lecture seule. Pour modifier la valeur, utilisez la propriété en lecture/écriture get_ParentSeriesGroup()->Overlap(). Lecture seule int8_t.
type: docs
weight: 690
url: /fr/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() méthode


Specifie combien les barres et les colonnes se chevauchent sur les graphiques 2-D, en pourcentage (de -100 % à 100 %). Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent. C’est une projection de la propriété appropriée dans le groupe de séries parent, et cette propriété est donc en lecture seule. Pour modifier la valeur, utilisez la propriété [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) en lecture/écriture. Lecture seule **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Remarques


Le chevauchement indique le degré de chevauchement ou d'espacement entre les barres et les colonnes en pourcentage de leur largeur:* -100 % : Espacement maximal (les barres sont complètement séparées).
* 0 % : Les barres sont placées côte à côte sans chevauchement ni espacement.
* 100 % : Chevauchement maximal (les barres se chevauchent entièrement). Ceci est une projection de la propriété [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/).


## Voir aussi

* Classe [ChartSeries](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)