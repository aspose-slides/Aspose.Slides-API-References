---
title: error_bars_x_format property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartseries/error_bars_x_format/
weight: 110
---
## error_bars_x_format propriété
Représente ErrorBars de la série avec la direction X.
            ErrorBars avec la direction X sont disponibles pour les séries de type area, bar, scatter et bubble.
            Pour tout autre type de graphique, cette propriété renvoie None (y compris les graphiques 3D).
            Dans le cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur
            (avec la propriété [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

            Lecture seule [`IErrorBarsFormat`](/slides/python-net/fr/aspose.slides.charts/ierrorbarsformat).

### Définition:
```python
@property
def error_bars_x_format(self):
    ...
```


### Voir aussi
* classe [`ChartSeries`](/slides/python-net/fr/aspose.slides.charts/chartseries)
* classe [`IErrorBarsFormat`](/slides/python-net/fr/aspose.slides.charts/ierrorbarsformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)