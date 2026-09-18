---
title: error_bars_x_format property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/ichartseries/error_bars_x_format/
weight: 110
---
## error_bars_x_format propriedade
Representa ErrorBars de séries com direção X. 
            
            ErrorBars com direção X estão disponíveis para séries do tipo area, bar, scatter e bubble. 
            Para quaisquer outros tipos de gráfico, esta propriedade retorna None (incluindo gráficos 3D).
            No caso de valores personalizados, use a coleção DataPoints para especificar o valor
            (com a propriedade [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/pt/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).
            
            Somente leitura [`IErrorBarsFormat`](/slides/python-net/pt/aspose.slides.charts/ierrorbarsformat).

### Definição:
```python
@property
def error_bars_x_format(self):
    ...
```


### Veja Também
* class [`IChartSeries`](/slides/python-net/pt/aspose.slides.charts/ichartseries)
* class [`IErrorBarsFormat`](/slides/python-net/pt/aspose.slides.charts/ierrorbarsformat)
* module [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)