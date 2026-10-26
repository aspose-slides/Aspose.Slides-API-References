---
title: get_ErrorBarsXFormat()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente les ErrorBars d'une série avec la direction X.
type: docs
weight: 222
url: /fr/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() méthode

Représente les ErrorBars d'une série avec la direction X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Remarques

Les ErrorBars avec direction X sont disponibles pour les séries de type area, bar, scatter et bubble. Pour tout autre type de graphique, cette propriété renvoie null (y compris les graphiques 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Lecture seule [IErrorBarsFormat](../../ierrorbarsformat/). 
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [ChartSeries](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)