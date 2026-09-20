---
title: ChartTitle class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/charttitle/
---
## ChartTitle klass

Representerar diagramtitelens egenskaper.

ChartTitle-typen avslöjar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`x`](/slides/python-net/sv/aspose.slides.charts/charttitle/x/) | Returnerar eller anger x-koordinaten för en titel som en bråkdel av diagrammets bredd.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides.charts/charttitle/y/) | Returnerar eller anger y-koordinaten för en titel som en bråkdel av diagrammets höjd.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides.charts/charttitle/width/) | Returnerar eller anger bredden för en titel som en bråkdel av diagrammets bredd.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides.charts/charttitle/height/) | Returnerar eller anger höjden för en titel som en bråkdel av diagrammets höjd.<br/>            Läs/skriv **float**. |
| [`right`](/slides/python-net/sv/aspose.slides.charts/charttitle/right/) | Höger.<br/>            Skrivskyddad **float**. |
| [`bottom`](/slides/python-net/sv/aspose.slides.charts/charttitle/bottom/) | Botten.<br/>            Skrivskyddad **float**. |
| [`overlay`](/slides/python-net/sv/aspose.slides.charts/charttitle/overlay/) | Bestämmer om andra diagramelement får överlappa titel.<br/>            Läs/skriv **bool**. |
| [`format`](/slides/python-net/sv/aspose.slides.charts/charttitle/format/) | Returnerar fyllnings-, linje- och effektstilar för en titel.<br/>            Skrivskyddad [`IFormat`](/slides/python-net/sv/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/sv/aspose.slides.charts/charttitle/text_frame_for_overriding/) | Kan innehålla rik formaterad text. Om denna egenskap inte är None så <br/>            åsidosätter detta formaterade textvärde automatiskt genererad text.<br/>            Automatisk genererad text är en implicit egenskap för datalabeln, enhetsetiketten för värdeaxeln, axelrubriken, diagramtiteln, trendlinjens etikett.<br/>            Automatisk genererad text formateras med IFormattedTextContainer.TextFormat-egenskapen.<br/>            Skrivskyddad [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/sv/aspose.slides.charts/charttitle/text_format/) | Returnerar textformat.<br/>            Skrivskyddad [`IChartTextFormat`](/slides/python-net/sv/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/sv/aspose.slides.charts/charttitle/actual_x/) | Anger faktisk x-position (vänster) för diagramelementet relativt diagrammets övre vänstra hörn.<br/>            Anropa metoden IChart.ValidateChartLayout() först för att få faktiska värden.<br/>            Läs **float**. |
| [`actual_y`](/slides/python-net/sv/aspose.slides.charts/charttitle/actual_y/) | Anger faktisk överkant för diagramelementet relativt diagrammets övre vänstra hörn.<br/>            Anropa metoden IChart.ValidateChartLayout() först för att få faktiska värden.<br/>            Läs **float**. |
| [`actual_width`](/slides/python-net/sv/aspose.slides.charts/charttitle/actual_width/) | Anger faktisk bredd för diagramelementet. Anropa metoden IChart.ValidateChartLayout() först för att få faktiska värden.<br/>            Läs **float**. |
| [`actual_height`](/slides/python-net/sv/aspose.slides.charts/charttitle/actual_height/) | Anger faktisk höjd för diagramelementet. Anropa metoden IChart.ValidateChartLayout() först för att få faktiska värden.<br/>            Läs **float**. |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/charttitle/chart/) | Returnerar föräldra-diagrammet.<br/>            Skrivskyddad [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/charttitle/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/sv/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | Initierar TextFrameForOverriding med texten i parametern "text".<br/>            Om TextFrameForOverriding redan är initierad ändras dess text helt enkelt. |

### Se också
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)