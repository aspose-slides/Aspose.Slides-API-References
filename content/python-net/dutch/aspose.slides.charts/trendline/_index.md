---
title: Trendline class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/trendline/
---
## Trendline klasse

De klasse vertegenwoordigt een trendlijn van een grafiekserie

Het Trendline-type geeft de volgende leden weer:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/nl/aspose.slides.charts/trendline/trendline_name/) | Haalt of stelt de naam van de trendlijn in.<br/>            Lezen/Schrijven **str**. |
| [`trendline_type`](/slides/python-net/nl/aspose.slides.charts/trendline/trendline_type/) | Haalt of stelt het type van de trendlijn in.<br/>            Lezen/Schrijven [`TrendlineType`](/slides/python-net/nl/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/nl/aspose.slides.charts/trendline/format/) | Stelt het formaat van de trendlijn voor.<br/>            Lezen/Schrijven [`IFormat`](/slides/python-net/nl/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/nl/aspose.slides.charts/trendline/backward/) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór<br/>            de gegevens voor de serie die wordt getrende. Bij spreidings- en niet-spreidingsgrafieken moet de waarde een niet-negatieve<br/>            waarde zijn.<br/>            Lezen/Schrijven **float**. |
| [`forward`](/slides/python-net/nl/aspose.slides.charts/trendline/forward/) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de<br/>            gegevens voor de serie die wordt getrende. Bij spreidings- en niet-spreidingsgrafieken moet de waarde een niet-negatieve<br/>            waarde zijn.<br/>            Lezen/Schrijven **float**. |
| [`intercept`](/slides/python-net/nl/aspose.slides.charts/trendline/intercept/) | Specificeert de waarde waarop de trendlijn de y-as kruist. Deze eigenschap wordt alleen ondersteund<br/>            wanneer het trendlijntype exp, lineair of poly is.<br/>            Lezen/Schrijven **float**. |
| [`display_equation`](/slides/python-net/nl/aspose.slides.charts/trendline/display_equation/) | Specificeert dat de vergelijking voor de trendlijn op de grafiek wordt weergegeven (in hetzelfde label als de Rsquaredvalue).<br/>            Lezen/Schrijven **bool**. |
| [`order`](/slides/python-net/nl/aspose.slides.charts/trendline/order/) | Specificeert de orde van de polynomiale trendlijn. Deze wordt genegeerd voor andere trendlijntypen. De waarde moet tussen 2 en 6 liggen.<br/>            Lezen/Schrijven **int**. |
| [`period`](/slides/python-net/nl/aspose.slides.charts/trendline/period/) | Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde. Deze wordt genegeerd voor andere trendlijn-varianten. De waarde moet tussen 2 en 255 liggen.<br/>            Lezen/Schrijven **int**. |
| [`display_r_squared_value`](/slides/python-net/nl/aspose.slides.charts/trendline/display_r_squared_value/) | Specificeert dat de R-kwadraatwaarde van de trendlijn op de grafiek wordt weergegeven (in hetzelfde label als de vergelijking).<br/>            Lezen/Schrijven **bool**. |
| [`related_legend_entry`](/slides/python-net/nl/aspose.slides.charts/trendline/related_legend_entry/) | Stelt de legende-vermelding voor die bij deze trendlijn hoort<br/>            Alleen-lezen [`ILegendEntryProperties`](/slides/python-net/nl/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/nl/aspose.slides.charts/trendline/text_frame_for_overriding/) | Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet None is, dan overschrijft deze <br/>            opgemaakte tekstwaarde de automatisch gegenereerde tekst van het gegevenslabel.<br/>            Automatisch gegenereerde tekst van het gegevenslabel betekent tekst die wordt beheerd door ShowSeriesName, <br/>            ShowValue, ... eigenschappen en wordt opgemaakt met de TextFormatManager.TextFormat-eigenschap.<br/>            Alleen-lezen [`ITextFrame`](/slides/python-net/nl/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/nl/aspose.slides.charts/trendline/text_format/) | Retourneert tekstopmaak.<br/>            Alleen-lezen [`IChartTextFormat`](/slides/python-net/nl/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/trendline/chart/) | Retourneert de bovenliggende grafiek.<br/>            Alleen-lezen [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/trendline/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/nl/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Initialiseert TextFrameForOverriding met de tekst in parameter "text".<br/>            Als TextFrameForOverriding al is geïnitialiseerd, wijzigt deze eenvoudigweg de tekst. |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)