---
title: ErrorBarsFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat klass

Representerar felstaplar för diagramserier. Anpassade värden för ErrorBars finns i IChartDataPointCollection (i [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) egenskapen).

ErrorBarsFormat-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`type`](/slides/python-net/sv/aspose.slides.charts/errorbarsformat/type/) | Hämtar eller anger typ av felstaplar. <br/>            Läs/skriv [`ErrorBarType`](/slides/python-net/sv/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/sv/aspose.slides.charts/errorbarsformat/value_type/) | Representerar möjliga sätt att bestämma längden på felstaplarna. <br/>            I fall av anpassat värde typ för att specificera värde, använd [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) egenskapen för en specifik datapunkt i DataPoints-samlingen av serien.<br/>            I fall av Fixed, Percentage eller StandardDeviation värdetyp, använd Value-egenskapen för att specificera värdet.  <br/>            Läs/skriv [`ErrorBarValueType`](/slides/python-net/sv/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/sv/aspose.slides.charts/errorbarsformat/has_end_cap/) | Specificerar att en ändkappa inte ritas på felstaplarna.<br/>            Läs/skriv **bool**. |
| [`value`](/slides/python-net/sv/aspose.slides.charts/errorbarsformat/value/) | Hämtar eller anger värde som används med Fixed, Percentage och StandardDeviation värdetyper för att bestämma längden på felstaplarna. <br/>            I alla andra fall returneras NaN.<br/>            Läs/skriv **float**. |
| [`format`](/slides/python-net/sv/aspose.slides.charts/errorbarsformat/format/) | Representerar formatet för felstaplarna.<br/>            Läs/skriv [`IFormat`](/slides/python-net/sv/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/errorbarsformat/chart/) | Returnerar det överordnade diagrammet.<br/>            Endast läsning [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/sv/aspose.slides.charts/errorbarsformat/is_visible/) | Hämtar eller anger synlighet för felstaplar.<br/>            Läs/skriv **bool**. |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)