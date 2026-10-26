---
title: get_ErrorBarsYFormat()
second_title: Referência da API Aspose.Slides para C++
description: Representa ErrorBars de séries com direção Y.
type: docs
weight: 235
url: /pt/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() método


Representa ErrorBars da série com direção Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Observações


ErrorBars com direção Y estão disponíveis para séries do tipo area, bar, line, scatter e bubble. Para quaisquer outros tipos de gráfico esta propriedade retorna null (incluindo gráficos 3D). No caso de valores personalizados, use a coleção DataPoints para especificar o valor (com [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) propriedade). 

Somente leitura [IErrorBarsFormat](../../ierrorbarsformat/). 
## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)