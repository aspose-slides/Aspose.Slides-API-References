---
title: IChartDataCell class
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell osztály

A diagram adatait tároló cellát képviseli.

Az IChartDataCell típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`row`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell/row/) | Visszaadja a munkalap azon sorának az indexét, amelyben a cella található.<br/>            Csak olvasható **int**. |
| [`column`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell/column/) | Visszaadja a munkalap azon oszlopának az indexét, amelyben a cella található.<br/>            Csak olvasható **int**. |
| [`value`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell/value/) | Lekérdezi vagy beállítja a cella értékét.<br/>            Olvasás/írás **any**. |
| [`formula`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell/formula/) | Lekérdezi vagy beállítja a képletet A1-stílusban. |
| [`r1c1_formula`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell/r1c1_formula/) | Lekérdezi vagy beállítja a képletet R1C1-stílusban. |
| [`chart_data_worksheet`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell/chart_data_worksheet/) | Lekérdezi a munkalapot.<br/>            Csak olvasható [`IChartDataWorksheet`](/slides/python-net/hu/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell/is_hidden/) | Megállapítja, hogy a cella rejtett-e.<br/>            Csak olvasható **bool**. |
| [`custom_number_format`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell/custom_number_format/) | Lekérdezi vagy beállítja a számok és dátumok egyéni megjelenítési formátumát.<br/>            Ha az érték üres, a PresetNumberFormat érték kerül felhasználásra.<br/>            Olvasás/írás **str**. |
| [`preset_number_format`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell/preset_number_format/) | Lekérdezi vagy beállítja a számok és dátumok beépített megjelenítési formátumát. A beépített számnak [0..22] vagy [37..49] tartományban kell lennie.<br/>             Olvasás/írás **int**. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell/calculate/#bool) | Ha a cella képletet tartalmaz, az érték a képlet alapján frissül. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)