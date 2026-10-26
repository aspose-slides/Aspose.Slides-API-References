---
title: ErrorBarsFormat class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat classe

Rappresenta le barre di errore di una serie del grafico. I valori personalizzati di ErrorBars si trovano in IChartDataPointCollection (nella proprietà [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

Il tipo ErrorBarsFormat espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/it/aspose.slides.charts/errorbarsformat/type/) | Ottiene o imposta il tipo di barre di errore. <br/> Lettura/Scrittura [`ErrorBarType`](/slides/python-net/it/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/it/aspose.slides.charts/errorbarsformat/value_type/) | Rappresenta i possibili modi per determinare la lunghezza delle barre di errore. <br/> In caso di tipo di valore personalizzato per specificare il valore, usare la proprietà [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) del punto dati specifico nella raccolta DataPoints della serie.<br/> In caso di tipo di valore Fixed, Percentage o StandardDeviation, utilizzare la proprietà Value per specificare il valore. <br/> Lettura/Scrittura [`ErrorBarValueType`](/slides/python-net/it/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/it/aspose.slides.charts/errorbarsformat/has_end_cap/) | Specifica che un cappuccio finale non è disegnato sulle barre di errore.<br/> Lettura/Scrittura **bool**. |
| [`value`](/slides/python-net/it/aspose.slides.charts/errorbarsformat/value/) | Ottiene o imposta il valore utilizzato con i tipi di valore Fixed, Percentage e StandardDeviation per determinare la lunghezza delle barre di errore. <br/> In qualsiasi altro caso ritornerà NaN.<br/> Lettura/Scrittura **float**. |
| [`format`](/slides/python-net/it/aspose.slides.charts/errorbarsformat/format/) | Rappresenta il formato delle barre di errore.<br/> Lettura/Scrittura [`IFormat`](/slides/python-net/it/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/it/aspose.slides.charts/errorbarsformat/chart/) | Restituisce il grafico padre.<br/> Solo lettura [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/it/aspose.slides.charts/errorbarsformat/is_visible/) | Ottiene o imposta la visibilità delle barre di errore.<br/> Lettura/Scrittura **bool**. |
| [`slide`](/slides/python-net/it/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)