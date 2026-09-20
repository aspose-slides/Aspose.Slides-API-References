---
title: DataLabel class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabel/
---
## DataLabel klass

Representerar serietiketter.

DataLabel-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/sv/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Skapar en ny instans av DataLabel klass. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/datalabel/chart/) | Returnerar det överordnade diagrammet.<br/>            Endast läs [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/sv/aspose.slides.charts/datalabel/is_visible/) | False betyder att datatetikett inte är synlig (och att alla Show*-flaggor (ShowValue, ...) är falska).<br/>            Endast läs **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/sv/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Kan innehålla en rik formaterad text. Om detta egenskap inte är None så åsidosätter detta <br/>            formaterade textvärde den automatiskt genererade texten för datatetikett.<br/>            Automatgenererad text för datatetikett betyder text som hanteras av ShowSeriesName, <br/>            ShowValue, ... egenskaper och formateras med TextFormatManager.TextFormat-egenskapen.<br/>            Endast läs [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/sv/aspose.slides.charts/datalabel/text_format/) | Returnerar textformat.<br/>            Endast läs [`IChartTextFormat`](/slides/python-net/sv/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/sv/aspose.slides.charts/datalabel/x/) | Returnerar eller anger x-koordinaten för en titel som en bråkdel av diagrammets bredd.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides.charts/datalabel/y/) | Returnerar eller anger y-koordinaten för en titel som en bråkdel av diagrammets höjd.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides.charts/datalabel/width/) | Returnerar eller anger bredden för en titel som en bråkdel av diagrammets bredd.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides.charts/datalabel/height/) | Returnerar eller anger höjden för en titel som en bråkdel av diagrammets höjd.<br/>            Läs/skriv **float**. |
| [`right`](/slides/python-net/sv/aspose.slides.charts/datalabel/right/) | Höger.<br/>            Endast läs **float**. |
| [`bottom`](/slides/python-net/sv/aspose.slides.charts/datalabel/bottom/) | Nederkant.<br/>            Endast läs **float**. |
| [`data_label_format`](/slides/python-net/sv/aspose.slides.charts/datalabel/data_label_format/) | Returnerar datatetikettformat.<br/>            Endast läs [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/sv/aspose.slides.charts/datalabel/value_from_cell/) | Hämtar eller anger arbetsbokens datacell. Tillämpas om IDataLabelFormat.ShowLabelValueFromCell-egenskapen är sann. |
| [`actual_x`](/slides/python-net/sv/aspose.slides.charts/datalabel/actual_x/) | Anger den faktiska x-positionen (vänster) för diagrammets element relativt diagrammets övre vänstra hörn.<br/>            Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. <br/>            Läs **float**. |
| [`actual_y`](/slides/python-net/sv/aspose.slides.charts/datalabel/actual_y/) | Anger den faktiska toppen för diagrammets element relativt diagrammets övre vänstra hörn.<br/>            Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. <br/>            Läs **float**. |
| [`actual_width`](/slides/python-net/sv/aspose.slides.charts/datalabel/actual_width/) | Anger den faktiska bredden för diagrammets element. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. <br/>            Läs **float**. |
| [`actual_height`](/slides/python-net/sv/aspose.slides.charts/datalabel/actual_height/) | Anger den faktiska höjden för diagrammets element. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. <br/>            Läs **float**. |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/datalabel/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`hide(self)`](/slides/python-net/sv/aspose.slides.charts/datalabel/hide/#) | Gör datatetikett dold genom att sätta alla Show*-flaggor (ShowValue, ...) till falskt läge.<br/>            IsVisible blir falskt efter detta. |
| [`get_actual_label_text(self)`](/slides/python-net/sv/aspose.slides.charts/datalabel/get_actual_label_text/#) | Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningar eller TextFrameForOverriding.Text-värde. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/sv/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Initierar TextFrameForOverriding med texten i parametern "text".<br/>            Om TextFrameForOverriding redan är initierad ändras dess text helt enkelt. |


### Se också
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)