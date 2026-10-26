---
title: ErrorBarsFormat class
second_title: Aspose.Slides a Python-hoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat osztály

A diagram sorozat hibavonalait képviseli. Az ErrorBars egyéni értékei az IChartDataPointCollection-ben találhatók (a [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) tulajdonságban).

Az ErrorBarsFormat típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/hu/aspose.slides.charts/errorbarsformat/type/) | Lekérdezi vagy beállítja a hibavonalak típusát. <br/>            Olvasás/írás [`ErrorBarType`](/slides/python-net/hu/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/hu/aspose.slides.charts/errorbarsformat/value_type/) | Ábrázolja a hibavonalak hosszának meghatározásának lehetséges módjait. <br/>            Egyéni értéktípus esetén az érték megadásához használja a [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) tulajdonságot a sorozat DataPoints gyűjteményének adott adatpontján.<br/>            Fixed, Percentage vagy StandardDeviation értéktípus esetén a Value tulajdonsággal adja meg az értéket.  <br/>            Olvasás/írás [`ErrorBarValueType`](/slides/python-net/hu/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/hu/aspose.slides.charts/errorbarsformat/has_end_cap/) | Megadja, hogy a hibavonalak végén nincs kapoccszorozó.<br/>            Olvasás/írás **bool**. |
| [`value`](/slides/python-net/hu/aspose.slides.charts/errorbarsformat/value/) | Lekérdezi vagy beállítja azt az értéket, amelyet Fixed, Percentage és StandardDeviation értéktípusokkal a hibavonalak hosszának meghatározásához használnak. <br/>            Minden más esetben NaN értéket ad vissza.<br/>            Olvasás/írás **float**. |
| [`format`](/slides/python-net/hu/aspose.slides.charts/errorbarsformat/format/) | Ábrázolja a hibavonalak formátumát.<br/>            Olvasás/írás [`IFormat`](/slides/python-net/hu/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/errorbarsformat/chart/) | Visszaadja a szülő diagramot.<br/>            Csak olvasható [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/hu/aspose.slides.charts/errorbarsformat/is_visible/) | Lekérdezi vagy beállítja a hibavonalak láthatóságát.<br/>            Olvasás/írás **bool**. |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)