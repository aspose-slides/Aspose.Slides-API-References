---
title: error_bars_y_format property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartseries/error_bars_y_format/
weight: 120
---
## error_bars_y_format propriété
Représente ErrorBars de séries avec la direction Y.
            
            ErrorBars avec direction Y sont disponibles pour les séries de type area, bar, line, scatter et bubble. 
            Pour tout autre type de graphique, cette propriété renvoie None (y compris les graphiques 3D). 
            Dans le cas de valeurs personnalisées, utilisez la collection DataPoints pour spécifier la valeur (avec la propriété [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).
            
            Lecture seule [`IErrorBarsFormat`](/slides/python-net/fr/aspose.slides.charts/ierrorbarsformat).

### Définition:
```python
@property
def error_bars_y_format(self):
    ...
```


### Voir aussi
* classe [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries)
* classe [`IErrorBarsFormat`](/slides/python-net/fr/aspose.slides.charts/ierrorbarsformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)