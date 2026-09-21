---
title: ErrorBarsFormat class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat klasse

Stelt foutbalken van een grafieksreeks voor. Aangepaste waarden van ErrorBars bevinden zich in IChartDataPointCollection (in [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) eigenschap).

Het type ErrorBarsFormat biedt de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`type`](/slides/python-net/nl/aspose.slides.charts/errorbarsformat/type/) | Haalt of stelt het type van foutbalken in. <br/>            Lezen/schrijven [`ErrorBarType`](/slides/python-net/nl/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/nl/aspose.slides.charts/errorbarsformat/value_type/) | Stelt mogelijke manieren voor om de lengte van de foutbalken te bepalen. <br/>            In het geval van een aangepast waardetype om een waarde op te geven, gebruik de [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) eigenschap van een specifiek gegevenspunt in de DataPoints-collectie van de reeks.<br/>            In het geval van Fixed, Percentage of StandardDeviation waardetype gebruik de Value eigenschap om een waarde op te geven.  <br/>            Lezen/schrijven [`ErrorBarValueType`](/slides/python-net/nl/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/nl/aspose.slides.charts/errorbarsformat/has_end_cap/) | Specificeert dat er geen eindkap op de foutbalken wordt getekend.<br/>            Lezen/schrijven **bool**. |
| [`value`](/slides/python-net/nl/aspose.slides.charts/errorbarsformat/value/) | Haalt of stelt de waarde in die wordt gebruikt met Fixed, Percentage en StandardDeviation waardetypen om de lengte van de foutbalken te bepalen. <br/>            In alle andere gevallen wordt NaN geretourneerd.<br/>            Lezen/schrijven **float**. |
| [`format`](/slides/python-net/nl/aspose.slides.charts/errorbarsformat/format/) | Stelt het formaat van de foutbalken voor.<br/>            Lezen/schrijven [`IFormat`](/slides/python-net/nl/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/errorbarsformat/chart/) | Retourneert de bovenliggende grafiek.<br/>            Alleen-lezen [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/nl/aspose.slides.charts/errorbarsformat/is_visible/) | Haalt of stelt de zichtbaarheid van Error Bars in.<br/>            Lezen/schrijven **bool**. |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)