---
title: get_PieSplitBy()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique en secteurs imbriqués ou en barres imbriquées. Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit de la projection de la propriété de groupe appropriée. Ainsi, cette propriété est en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez get_ParentSeriesGroup()->get(set)_PieSplitBy() propriété en lecture/écriture pour modifier la valeur. PieSplitType en lecture seule.
type: docs
weight: 729
url: /fr/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() méthode

Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre d'un graphique en secteurs imbriqués ou en barres imbriquées. Il s'agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s'agit de la projection de la propriété de groupe appropriée. Ainsi, cette propriété est en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() propriété en lecture/écriture pour modifier la valeur. Lecture seule [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Remarques

1) Il s'agit de la projection de la propriété [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Si la valeur de la propriété est [PieSplitType::Custom](../../piesplittype/) alors vous pouvez définir des informations de division personnalisées avec la propriété [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Voir aussi

* Énumération [PieSplitType](../../piesplittype/)
* Classe [IChartSeries](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)