---
title: get_ErrorBarsYFormat()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta ErrorBars della serie con direzione Y.
type: docs
weight: 235
url: /it/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() metodo

Rappresenta ErrorBars della serie con direzione Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Osservazioni

ErrorBars con direzione Y sono disponibili per le serie di tipo area, bar, line, scatter e bubble. Per qualsiasi altro tipo di grafico questa proprietà restituisce null (inclusi i grafici 3D). In caso di valori personalizzati, utilizzare la raccolta DataPoints per specificare il valore (con la proprietà [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Solo lettura [IErrorBarsFormat](../../ierrorbarsformat/). 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IErrorBarsFormat](../../ierrorbarsformat/)
* Classe [IChartSeries](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)