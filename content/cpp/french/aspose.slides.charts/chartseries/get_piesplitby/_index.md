---
title: get_PieSplitBy()
second_title: Référence de l'API Aspose.Slides for C++
description: Spécifie comment déterminer quels points de données se trouvent dans la deuxième part ou barre d’un graphique en anneaux ou en barres d’un diagramme en anneaux ou en barres. Il s’agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s’agit de la projection de la propriété de groupe appropriée. Ainsi, cette propriété est en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez la propriété get_ParentSeriesGroup()->get(set)_PieSplitBy() en lecture/écriture pour modifier la valeur. PieSplitType en lecture seule.
type: docs
weight: 755
url: /fr/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() méthode

Spécifie comment déterminer quels points de données se trouvent dans la deuxième part ou barre d’un diagramme en anneaux ou en barres d’un graphique en anneaux ou en barres. Il s’agit de la propriété non seulement de cette série mais de toutes les séries du groupe de séries parent – il s’agit de la projection de la propriété de groupe appropriée. Ainsi, cette propriété est en lecture seule. Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent. Utilisez [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() propriété lecture/écriture pour modifier la valeur. Lecture seule [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Remarques

1) C’est la projection de la propriété [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Si la valeur de la propriété est [PieSplitType::Custom](../../piesplittype/) alors vous pouvez définir des informations de division personnalisées avec la propriété [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Voir aussi

* Enum [PieSplitType](../../piesplittype/)
* classe [ChartSeries](../)
* espace de noms [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)