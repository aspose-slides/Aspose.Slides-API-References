---
title: get_ErrorBarsYFormat()
second_title: Referência da API Aspose.Slides para C++
description: Representa ErrorBars da série com direção Y.
type: docs
weight: 235
url: /pt/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() método

Representa ErrorBars da série com direção Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Observações

ErrorBars com direção Y estão disponíveis para séries do tipo area, bar, line, scatter e bubble. Para quaisquer outros tipos de gráfico esta propriedade retorna null (incluindo gráficos 3D). No caso de valores personalizados, use a coleção DataPoints para especificar o valor (com a propriedade [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Somente leitura [IErrorBarsFormat](../../ierrorbarsformat/). 
## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [ChartSeries](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)