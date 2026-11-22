---
title: DataLabel class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabel/
---
## DataLabel-klass

Representerar serietiketter.

DataLabel-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/sv/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Skapar en ny instans av DataLabel-klass. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/datalabel/chart/) | Returnerar föräldrakartan.<br/>            Read-only [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/sv/aspose.slides.charts/datalabel/is_visible/) | False betyder att datamärket inte är synligt (och att alla Show*-flaggor (ShowValue, ...) är falska).<br/>            Read-only **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/sv/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Kan innehålla rik formaterad text. Om denna egenskap inte är None så överskrivs det <br/>            formaterade textvärdet den automatiskt genererade texten för datamärket.<br/>            Automatisk genererad text för datamärket betyder text som hanteras av ShowSeriesName, <br/>            ShowValue, ... egenskaper och formateras med TextFormatManager.TextFormat-egenskapen.<br/>            Read-only [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/sv/aspose.slides.charts/datalabel/text_format/) | Returnerar textformat.<br/>            Read-only [`IChartTextFormat`](/slides/python-net/sv/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/sv/aspose.slides.charts/datalabel/x/) | Returnerar eller anger x-koordinaten för en rubrik som en bråkdel av diagrammets bredd.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/sv/aspose.slides.charts/datalabel/y/) | Returnerar eller anger y-koordinaten för en rubrik som en bråkdel av diagrammets höjd.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/sv/aspose.slides.charts/datalabel/width/) | Returnerar eller anger bredden för en rubrik som en bråkdel av diagrammets bredd.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/sv/aspose.slides.charts/datalabel/height/) | Returnerar eller anger höjden för en rubrik som en bråkdel av diagrammets höjd.<br/>            Read/write **float**. |
| [`right`](/slides/python-net/sv/aspose.slides.charts/datalabel/right/) | Höger.<br/>            Read-only **float**. |
| [`bottom`](/slides/python-net/sv/aspose.slides.charts/datalabel/bottom/) | Nederkant.<br/>            Read-only **float**. |
| [`data_label_format`](/slides/python-net/sv/aspose.slides.charts/datalabel/data_label_format/) | Returnerar datamärkesformat.<br/>            Read-only [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/sv/aspose.slides.charts/datalabel/value_from_cell/) | Hämtar eller anger arbetsboksdatacell. Tillämpas om IDataLabelFormat.ShowLabelValueFromCell-egenskapen är sann. |
| [`label_shape_type`](/slides/python-net/sv/aspose.slides.charts/datalabel/label_shape_type/) | Hämtar eller anger formtypen för datamärket.<br/>             Returnerar [`ShapeType.NOT_DEFINED`](/slides/python-net/sv/aspose.slides/shapetype/NOT_DEFINED) om ingen form är definierad. |
| [`actual_x`](/slides/python-net/sv/aspose.slides.charts/datalabel/actual_x/) | Anger faktiskt x-läge (vänster) för diagramelementet relativt diagrammets övre vänstra hörn.<br/>            Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden.<br/>            Read **float**. |
| [`actual_y`](/slides/python-net/sv/aspose.slides.charts/datalabel/actual_y/) | Anger faktiskt övre läge för diagramelementet relativt diagrammets övre vänstra hörn.<br/>            Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden.<br/>            Read **float**. |
| [`actual_width`](/slides/python-net/sv/aspose.slides.charts/datalabel/actual_width/) | Anger faktiskt bredd för diagramelementet. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden.<br/>            Read **float**. |
| [`actual_height`](/slides/python-net/sv/aspose.slides.charts/datalabel/actual_height/) | Anger faktiskt höjd för diagramelementet. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden.<br/>            Read **float**. |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/datalabel/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`hide(self)`](/slides/python-net/sv/aspose.slides.charts/datalabel/hide/#) | Gör datamärket dolt genom att sätta alla Show*-flaggor (ShowValue, ...) till falskt läge.<br/>            IsVisible blir falskt efter detta. |
| [`get_actual_label_text(self)`](/slides/python-net/sv/aspose.slides.charts/datalabel/get_actual_label_text/#) | Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningar eller TextFrameForOverriding.Text-värde. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/sv/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Initierar TextFrameForOverriding med texten i parametern "text".<br/>            Om TextFrameForOverriding redan är initierad ändras dess text enkelt. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)