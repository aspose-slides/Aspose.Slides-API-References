---
title: get_ErrorBarsXFormat()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta le ErrorBars della serie con direzione X.
type: docs
weight: 222
url: /it/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() metodo

Rappresenta le ErrorBars della serie con direzione X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Osservazioni

Le ErrorBars con direzione X sono disponibili per le serie di tipo area, bar, scatter e bubble. Per qualsiasi altro tipo di grafico questa proprietà restituisce null (inclusi i grafici 3D). Nel caso di valori personalizzati, utilizzare la collezione DataPoints per specificare il valore (con la proprietà [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Di sola lettura [IErrorBarsFormat](../../ierrorbarsformat/).
## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)