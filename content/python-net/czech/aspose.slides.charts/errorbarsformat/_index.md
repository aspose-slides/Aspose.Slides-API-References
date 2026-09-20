---
title: ErrorBarsFormat class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat třída

Reprezentuje chybové pruhy řady grafu. Vlastní hodnoty ErrorBars jsou v IChartDataPointCollection (v [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) vlastnosti).

Typ ErrorBarsFormat obsahuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/cs/aspose.slides.charts/errorbarsformat/type/) | Získává nebo nastavuje typ chybových pruhů. <br/>            Čtení/zápis [`ErrorBarType`](/slides/python-net/cs/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/cs/aspose.slides.charts/errorbarsformat/value_type/) | Reprezentuje možné způsoby určení délky chybových pruhů. <br/>            V případě vlastního typu hodnoty pro určení hodnoty použijte [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) vlastnost konkrétního datového bodu ve sbírce DataPoints řady.<br/>            V případě typu hodnoty Fixed, Percentage nebo StandardDeviation použijte vlastnost Value pro zadání hodnoty.  <br/>            Čtení/zápis [`ErrorBarValueType`](/slides/python-net/cs/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/cs/aspose.slides.charts/errorbarsformat/has_end_cap/) | Určuje, že koncová čepička není kreslena na chybových pruzích.<br/>            Čtení/zápis **bool**. |
| [`value`](/slides/python-net/cs/aspose.slides.charts/errorbarsformat/value/) | Získává nebo nastavuje hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových pruhů. <br/>            V ostatních případech vrátí NaN.<br/>            Čtení/zápis **float**. |
| [`format`](/slides/python-net/cs/aspose.slides.charts/errorbarsformat/format/) | Reprezentuje formát chybových pruhů.<br/>            Čtení/zápis [`IFormat`](/slides/python-net/cs/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/errorbarsformat/chart/) | Vrací nadřazený graf.<br/>            Pouze pro čtení [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/cs/aspose.slides.charts/errorbarsformat/is_visible/) | Získává nebo nastavuje viditelnost chybových pruhů.<br/>            Čtení/zápis **bool**. |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)