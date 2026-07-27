---
title: get_ErrorBarsXFormat()
second_title: Referência da API Aspose.Slides para C++
description: Representa ErrorBars da série com direção X.
type: docs
weight: 222
url: /pt/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() método

Representa ErrorBars da série com direção X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Observações

ErrorBars com direção X estão disponíveis para séries do tipo area, bar, scatter e bubble. Para qualquer outro tipo de gráfico esta propriedade retorna null (incluindo gráficos 3D). No caso de valores personalizados use a coleção DataPoints para especificar o valor (com a propriedade [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Somente leitura [IErrorBarsFormat](../../ierrorbarsformat/).
## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [ChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)