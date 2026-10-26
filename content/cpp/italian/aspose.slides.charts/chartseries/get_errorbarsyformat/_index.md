---
title: get_ErrorBarsYFormat()
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta ErrorBars della serie con direzione Y.
type: docs
weight: 235
url: /it/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() metodo

Rappresenta le ErrorBars della serie con direzione Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Osservazioni

ErrorBars con direzione Y sono disponibili per serie di tipo area, barra, linea, dispersione e bolla. Per tutti gli altri tipi di grafico questa proprietà restituisce null (inclusi i grafici 3D). In caso di valori personalizzati utilizzare la collezione DataPoints per specificare il valore (con la proprietà [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Sola lettura [IErrorBarsFormat](../../ierrorbarsformat/). 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [ChartSeries](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)