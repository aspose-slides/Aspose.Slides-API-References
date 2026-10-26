---
title: get_Overlap()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie le degré de chevauchement des barres et des colonnes sur des graphiques 2-D, exprimé en pourcentage (de -100% à 100%). Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent. C'est une projection de la propriété appropriée dans le groupe de séries parent, et cette propriété est en lecture seule. Pour modifier la valeur, utilisez la propriété lecture/écriture get_ParentSeriesGroup()->get(set)_Overlap(). Lecture seule int8_t.
type: docs
weight: 690
url: /fr/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() méthode

Spécifie le degré de chevauchement des barres et des colonnes sur des graphiques 2-D, exprimé en pourcentage (de -100% à 100%). Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent. C'est une projection de la propriété correspondante dans le groupe de séries parent, et cette propriété est en lecture seule. Pour modifier la valeur, utilisez la propriété lecture/écriture [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap(). Lecture seule **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Remarques

Le chevauchement spécifie le degré de chevauchement ou d'espacement entre les barres et les colonnes en pourcentage de leur largeur:* -100%: Espacement maximal (les barres sont complètement séparées).
* 0%: Les barres sont placées côte à côte sans chevauchement ni espacement.
* 100%: Chevauchement maximal (les barres se chevauchent complètement). Il s'agit d'une projection de la propriété [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().

## Voir aussi

* Classe [IChartSeries](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)