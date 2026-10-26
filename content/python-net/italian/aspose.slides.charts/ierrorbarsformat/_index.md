---
title: IErrorBarsFormat class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ierrorbarsformat/
---
## IErrorBarsFormat classe

Rappresenta le barre di errore di una serie di grafico. I valori personalizzati di ErrorBars si trovano in IChartDataPointCollection (nella proprietà [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

Il tipo IErrorBarsFormat espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`type`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat/type/) | Ottiene o imposta il tipo di barre di errore. <br/>            Lettura/scrittura [`ErrorBarType`](/slides/python-net/it/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat/value_type/) | Rappresenta i possibili modi per determinare la lunghezza delle barre di errore. <br/>            In caso di tipo di valore personalizzato per specificare il valore, utilizzare la proprietà [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) del punto dati specifico nella raccolta DataPoints della serie.  <br/>            Lettura/scrittura [`ErrorBarValueType`](/slides/python-net/it/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat/has_end_cap/) | Specifica che non viene disegnato un cappuccio finale sulle barre di errore.<br/>            Lettura/scrittura **bool**. |
| [`value`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat/value/) | Ottiene o imposta il valore utilizzato con i tipi di valore Fixed, Percentage e StandardDeviation per determinare la lunghezza delle barre di errore. <br/>            Lettura/scrittura **float**. |
| [`format`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat/format/) | Rappresenta il formato delle barre di errore.<br/>            Lettura/scrittura [`IFormat`](/slides/python-net/it/aspose.slides.charts/iformat). |
| [`is_visible`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat/is_visible/) | Ottiene o imposta la visibilità delle barre di errore.<br/>            Lettura/scrittura **bool**. |
| [`chart`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat/chart/) |  |
| [`slide`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/ierrorbarsformat/presentation/) |  |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)