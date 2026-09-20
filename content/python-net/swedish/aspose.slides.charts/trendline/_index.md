---
title: Trendline class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/trendline/
---
## Trendline klass

Klassen representerar en trendlinje för diagramserie

The Trendline type exposes the following members:

## Egenskap

| Egenskap | Beskrivning |
| :- | :- |
| [`trendline_name`](/slides/python-net/sv/aspose.slides.charts/trendline/trendline_name/) | Hämtar eller anger namnet på trendlinjen.<br/>            Läs/skriv **str**. |
| [`trendline_type`](/slides/python-net/sv/aspose.slides.charts/trendline/trendline_type/) | Hämtar eller anger typen av trendlinje.<br/>            Läs/skriv [`TrendlineType`](/slides/python-net/sv/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/sv/aspose.slides.charts/trendline/format/) | Representerar formatet för trendlinjen.<br/>            Läs/skriv [`IFormat`](/slides/python-net/sv/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/sv/aspose.slides.charts/trendline/backward/) | Anger antalet kategorier (eller enheter i ett spridningsdiagram) som trendlinjen sträcker sig före<br/>            data för den serie som trenderas. I spridnings- och icke-spridningsdiagram ska värdet vara ett icke-negativt<br/>            värde.<br/>            Läs/skriv **float**. |
| [`forward`](/slides/python-net/sv/aspose.slides.charts/trendline/forward/) | Anger antalet kategorier (eller enheter i ett spridningsdiagram) som trendlinjen sträcker sig efter<br/>            data för den serie som trenderas. I spridnings- och icke-spridningsdiagram ska värdet vara ett icke-negativt<br/>            värde.<br/>            Läs/skriv **float**. |
| [`intercept`](/slides/python-net/sv/aspose.slides.charts/trendline/intercept/) | Anger värdet där trendlinjen ska korsa y-axeln. Denna egenskap stöds endast<br/>            när trendlinjetypen är exp, linear eller poly.<br/>            Läs/skriv **float**. |
| [`display_equation`](/slides/python-net/sv/aspose.slides.charts/trendline/display_equation/) | Anger att ekvationen för trendlinjen visas i diagrammet (i samma etikett som Rsquaredvalue).<br/>            Läs/skriv **bool**. |
| [`order`](/slides/python-net/sv/aspose.slides.charts/trendline/order/) | Anger ordningen för den polynomiska trendlinjen. Den ignoreras för andra trendlinjetyper. Värdet måste vara mellan 2 och 6.<br/>            Läs/skriv **int**. |
| [`period`](/slides/python-net/sv/aspose.slides.charts/trendline/period/) | Anger perioden för trendlinjen för ett glidande medelvärde. Den ignoreras för andra trend-<br/>            variant. Värdet måste vara mellan 2 och 255.<br/>            Läs/skriv **int**. |
| [`display_r_squared_value`](/slides/python-net/sv/aspose.slides.charts/trendline/display_r_squared_value/) | Anger att R-kvadrerat-värdet för trendlinjen visas i diagrammet (i samma etikett som ekvationen).<br/>            Läs/skriv **bool**. |
| [`related_legend_entry`](/slides/python-net/sv/aspose.slides.charts/trendline/related_legend_entry/) | Representerar legendposten som är relaterad till denna trendlinje<br/>            Skrivskyddad [`ILegendEntryProperties`](/slides/python-net/sv/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/sv/aspose.slides.charts/trendline/text_frame_for_overriding/) | Kan innehålla rik formaterad text. Om denna egenskap inte är None så <br/>            åsidosätter detta formaterade textvärde den automatiskt genererade texten för datamärket.<br/>            Automatisk genererad text för datamärket betyder text som hanteras av ShowSeriesName, <br/>            ShowValue, ... egenskaper och som formateras med TextFormatManager.TextFormat-egenskapen.<br/>            Skrivskyddad [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/sv/aspose.slides.charts/trendline/text_format/) | Returnerar textformat.<br/>            Skrivskyddad [`IChartTextFormat`](/slides/python-net/sv/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/trendline/chart/) | Returnerar det överordnade diagrammet.<br/>            Skrivskyddad [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/trendline/presentation/) |  |

## Metod

| Metod | Beskrivning |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/sv/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Initierar TextFrameForOverriding med texten i parametern "text".<br/>            Om TextFrameForOverriding redan är initierad ändras dess text helt enkelt. |

### Se också
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)