---
title: error_bars_x_format property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartseries/error_bars_x_format/
weight: 110
---
## error_bars_x_format vlastnost
Zastupuje ErrorBars řady se směrem X. 
            
            ErrorBars se směrem X jsou k dispozici pro řady typu area, bar, scatter a bubble. 
            Pro jakékoli jiné typy grafu tato vlastnost vrací None (včetně 3D grafů).
            V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty
            (s [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) vlastností).
            
            Pouze pro čtení [`IErrorBarsFormat`](/slides/python-net/cs/aspose.slides.charts/ierrorbarsformat).

### Definice:
```python
@property
def error_bars_x_format(self):
    ...
```


### Viz také
* třída [`ChartSeries`](/slides/python-net/cs/aspose.slides.charts/chartseries)
* třída [`IErrorBarsFormat`](/slides/python-net/cs/aspose.slides.charts/ierrorbarsformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)