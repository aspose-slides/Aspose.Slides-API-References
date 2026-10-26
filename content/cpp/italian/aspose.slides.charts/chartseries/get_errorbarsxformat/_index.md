---
title: get_ErrorBarsXFormat()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta ErrorBars della serie con direzione X.
type: docs
weight: 222
url: /it/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() metodo

Rappresenta ErrorBars della serie con direzione X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Osservazioni

ErrorBars con direzione X sono disponibili per serie di tipo area, bar, scatter e bubble. Per qualsiasi altro tipo di grafico questa proprietà restituisce null (inclusi i grafici 3D). In caso di valori personalizzati, utilizzare la collezione DataPoints per specificare il valore (con la proprietà [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Solo lettura [IErrorBarsFormat](../../ierrorbarsformat/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [ChartSeries](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)