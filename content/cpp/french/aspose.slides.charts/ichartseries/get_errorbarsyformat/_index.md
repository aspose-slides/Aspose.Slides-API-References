---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Représente les ErrorBars d'une série avec la direction Y.
type: docs
weight: 235
url: /fr/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() méthode


Représente les ErrorBars d'une série avec la direction Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Remarques


Les ErrorBars avec direction Y sont disponibles pour les séries de type area, bar, line, scatter et bubble. Pour tous les autres types de graphique, cette propriété renvoie null (y compris les graphiques 3D). En cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Lecture seule [IErrorBarsFormat](../../ierrorbarsformat/). 
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [IChartSeries](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)