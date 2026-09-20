---
title: IChartDataCell class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell klass

Representerar cell för diagramdata.

IChartDataCell-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`row`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell/row/) | Returns the index of the row of worksheet in which the cell is located.<br/>            Read-only **int**. |
| [`column`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell/column/) | Returns the index of the column of worksheet in which the cell is located.<br/>            Read-only **int**. |
| [`value`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell/value/) | Hämtar eller anger värdet på en cell.<br/>            Read/write **any**. |
| [`formula`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell/formula/) | Hämtar eller anger formeln i A1-stil. |
| [`r1c1_formula`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell/r1c1_formula/) | Hämtar eller anger formeln i R1C1-stil. |
| [`chart_data_worksheet`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell/chart_data_worksheet/) | Hämtar kalkylbladet.<br/>            Read-only [`IChartDataWorksheet`](/slides/python-net/sv/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell/is_hidden/) | Avgör om cellen är dold.<br/>            Read-only **bool**. |
| [`custom_number_format`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell/custom_number_format/) | Hämtar eller anger det anpassade visningsformatet för tal och datum. <br/>            Om värdet är tomt kommer PresetNumberFormat-värdet att användas.<br/>            Read/write **str**. |
| [`preset_number_format`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell/preset_number_format/) | Hämtar eller anger det inbyggda visningsformatet för tal och datum. Preset number must be in [0..22] or [37..49].<br/>            Read/write **int**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/sv/aspose.slides.charts/ichartdatacell/calculate/#bool) | Om cellen innehåller en formel uppdateras värdet baserat på den formeln. |


### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)