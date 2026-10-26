---
title: get_ErrorBarsXFormat()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente les ErrorBars de la série avec la direction X.
type: docs
weight: 222
url: /fr/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() méthode

Représente les ErrorBars de la série avec la direction X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Remarques

Les ErrorBars avec direction X sont disponibles pour les séries de type area, bar, scatter et bubble. Pour tout autre type de diagramme, cette propriété renvoie null (y compris les diagrammes 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Lecture seule [IErrorBarsFormat](../../ierrorbarsformat/). 
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [IChartSeries](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)