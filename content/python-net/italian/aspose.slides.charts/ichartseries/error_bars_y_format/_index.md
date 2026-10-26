---
title: error_bars_y_format property
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartseries/error_bars_y_format/
weight: 120
---
## error_bars_y_format proprietà
Rappresenta ErrorBars di una serie con direzione Y.

ErrorBars con direzione Y sono disponibili per le serie di tipo area, bar, line, scatter e bubble.  
Per tutti gli altri tipi di grafico questa proprietà restituisce None (inclusi i grafici 3D).  
Nel caso di valori personalizzati, utilizza la collezione DataPoints per specificare il valore (con la proprietà [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

Solo lettura [`IErrorBarsFormat`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat).

### Definizione:
```python
@property
def error_bars_y_format(self):
    ...
```

### Vedi anche
* classe [`IChartSeries`](/slides/python-net/it/aspose.slides.charts/ichartseries)
* classe [`IErrorBarsFormat`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)