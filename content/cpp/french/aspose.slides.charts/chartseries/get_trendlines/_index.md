---
title: get_TrendLines()
second_title: Référence de l'API Aspose.Slides pour C++
description: Collection de lignes de tendance de séries. Lecture seule ITrendlineCollection.
type: docs
weight: 209
url: /fr/aspose.slides.charts/chartseries/get_trendlines/
---
## ChartSeries::get_TrendLines() méthode


Collection de lignes de tendance de séries. Lecture seule [ITrendlineCollection](../../itrendlinecollection/).

```cpp
System::SharedPtr<ITrendlineCollection> Aspose::Slides::Charts::ChartSeries::get_TrendLines() override
```

## Remarques


TrendLines sont disponibles (non null) pour les séries de données dans les graphiques unstacked 2-D area, bar, column, line, stock, xy (scatter) et bubble. Une trendline n'est pas disponible pour les séries de données dans tout type de graphique qui est stacked ou 3-D. Trendlines ne sont également pas disponibles pour les graphiques radar, pie, surface ou doughnut. 
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITrendlineCollection](../../itrendlinecollection/)
* Classe [ChartSeries](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)