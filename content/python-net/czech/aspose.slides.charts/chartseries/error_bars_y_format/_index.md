---
title: error_bars_y_format property
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides.charts/chartseries/error_bars_y_format/
weight: 120
---
## error_bars_y_format property
Představuje ErrorBars řady se směrem Y.

            ErrorBars se směrem Y jsou k dispozici pro řady typu area, bar, line, scatter a bubble. 
            Pro všechny ostatní typy grafu tato vlastnost vrací None (včetně 3D grafů). 
            V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty
            (s vlastností [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

            Pouze pro čtení [`IErrorBarsFormat`](/slides/python-net/cs/aspose.slides.charts/ierrorbarsformat).

### Definice:
```python
@property
def error_bars_y_format(self):
    ...
```


### Viz také
* třída [`ChartSeries`](/slides/python-net/cs/aspose.slides.charts/chartseries)
* třída [`IErrorBarsFormat`](/slides/python-net/cs/aspose.slides.charts/ierrorbarsformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)