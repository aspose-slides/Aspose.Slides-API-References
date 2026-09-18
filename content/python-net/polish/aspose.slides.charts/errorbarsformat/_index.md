---
title: ErrorBarsFormat class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat klasa

Reprezentuje ErrorBars serii wykresu. ErrorBars custom values are in IChartDataPointCollection (in [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) property).

Typ ErrorBarsFormat udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/pl/aspose.slides.charts/errorbarsformat/type/) | Pobiera lub ustawia typ słupków błędów. <br/>            Odczyt/zapis [`ErrorBarType`](/slides/python-net/pl/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/pl/aspose.slides.charts/errorbarsformat/value_type/) | Reprezentuje możliwe sposoby określenia długości słupków błędów. <br/>            W przypadku typu wartości niestandardowej, aby określić wartość, użyj właściwości [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) konkretnego punktu danych w kolekcji DataPoints serii.<br/>            W przypadku typów wartości Fixed, Percentage lub StandardDeviation użyj właściwości Value, aby określić wartość.  <br/>            Odczyt/zapis [`ErrorBarValueType`](/slides/python-net/pl/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/pl/aspose.slides.charts/errorbarsformat/has_end_cap/) | Określa, że zakończenie nie jest rysowane na słupkach błędów.<br/>            Odczyt/zapis **bool**. |
| [`value`](/slides/python-net/pl/aspose.slides.charts/errorbarsformat/value/) | Pobiera lub ustawia wartość używaną z typami wartości Fixed, Percentage i StandardDeviation do określenia długości słupków błędów. <br/>            W każdym innym przypadku zwróci NaN.<br/>            Odczyt/zapis **float**. |
| [`format`](/slides/python-net/pl/aspose.slides.charts/errorbarsformat/format/) | Reprezentuje format słupków błędów.<br/>            Odczyt/zapis [`IFormat`](/slides/python-net/pl/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/errorbarsformat/chart/) | Zwraca wykres nadrzędny.<br/>            Tylko do odczytu [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/pl/aspose.slides.charts/errorbarsformat/is_visible/) | Pobiera lub ustawia widoczność słupków błędów.<br/>            Odczyt/zapis **bool**. |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/errorbarsformat/presentation/) |  |


### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)