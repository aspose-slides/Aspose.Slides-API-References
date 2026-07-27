---
title: get_ErrorBarsXFormat()
second_title: Referência da API Aspose.Slides for C++
description: Representa ErrorBars da série com direção X.
type: docs
weight: 222
url: /pt/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() método


Representa ErrorBars da série com direção X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Observações


ErrorBars com direção X estão disponíveis para séries do tipo area, bar, scatter e bubble. Para qualquer outro tipo de gráfico esta propriedade retorna null (incluindo gráficos 3D). No caso de valores personalizados, use a coleção DataPoints para especificar o valor (com a propriedade [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Somente leitura [IErrorBarsFormat](../../ierrorbarsformat/). 
## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)