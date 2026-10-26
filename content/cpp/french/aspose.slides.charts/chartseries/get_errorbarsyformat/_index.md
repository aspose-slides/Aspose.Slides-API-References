---
title: get_ErrorBarsYFormat()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente les ErrorBars de la série avec la direction Y.
type: docs
weight: 235
url: /fr/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() méthode

Représente les ErrorBars de la série avec la direction Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Remarques

Les ErrorBars avec direction Y sont disponibles pour les séries de type area, bar, line, scatter et bubble. Pour tout autre type de graphique, cette propriété renvoie null (y compris les graphiques 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Lecture seule [IErrorBarsFormat](../../ierrorbarsformat/). 
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [ChartSeries](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)