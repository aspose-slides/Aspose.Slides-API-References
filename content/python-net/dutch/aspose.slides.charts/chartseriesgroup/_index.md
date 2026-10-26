---
title: ChartSeriesGroup class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasse

Stelt een groep series voor.

Het type ChartSeriesGroup exposeert de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`type`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/type/) | Retourneert een type van deze seriesgroep.<br/>            Alleen-lezen [`CombinableSeriesTypesGroup`](/slides/python-net/nl/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Geeft aan of series van deze groep wordt weergegeven op een secundaire as.<br/>            Alleen-lezen **bool**. |
| [`series`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/series/) | Retourneert een collectie van series.<br/>            Alleen-lezen [`IChartSeriesReadonlyCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Biedt toegang tot op/neer-balken van een lijn- of aandelen-grafiek.<br/>            Alleen-lezen [`IUpDownBarsManager`](/slides/python-net/nl/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/gap_width/) | Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de breedte van de balk of kolom.<br/>            Lezen/schrijven **int**. |
| [`gap_depth`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/gap_depth/) | Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de dataseries in een 3D-grafiek.<br/>            Lezen/schrijven **int**. |
| [`first_slice_angle`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Haalt of stelt de hoek van het eerste taart- of donut-grafieksegment in, <br/>            in graden (met de klok mee vanaf boven, van 0 tot 360 graden).<br/>            Lezen/schrijven **int**. |
| [`doughnut_hole_size`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Specificeert de grootte van het gat in een donut-grafiek (kan tussen 0 en 90 procent van de grootte van het plot-gebied liggen).<br/>            Lezen/schrijven **int**. |
| [`overlap`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/overlap/) | Specificeert hoeveel balken en kolommen op 2-D-grafieken moeten overlappen, als percentage (van -100 % tot 100 %).<br/>             - -100 %: Maximale ruimte (balken zijn volledig gescheiden).<br/>             - 0 %: Balken liggen naast elkaar zonder overlap of ruimte.<br/>             - 100 %: Maximale overlap (balken overlappen volledig elkaar).<br/>             Deze eigenschap is lezen/schrijven **int**. |
| [`second_pie_size`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Specificeert de grootte van de tweede taart of balk van een taart-in-taart-grafiek of een balk-in-taart-grafiek, als percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen).<br/>            Lezen/schrijven **int**. |
| [`bubble_size_representation`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Specificeert hoe de waarden voor bubbelgroottes worden weergegeven op de bubbelgrafiek.<br/>            Lezen/schrijven [`BubbleSizeRepresentationType`](/slides/python-net/nl/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Specificeert een waarde die wordt gebruikt om te bepalen welke datapunten zich in de tweede taart of balk bevinden op een taart-in-taart- of balk-in-taart-grafiek.<br/>            Wordt samen met de eigenschap PieSplitBy gebruikt.<br/>            Lezen/schrijven **float**. |
| [`pie_split_by`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Specificeert hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden op een taart-in-taart- of balk-in-taart-grafiek.<br/>            Lezen/schrijven [`PieSplitType`](/slides/python-net/nl/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Geeft aan dat elke datamarker in de serie een andere kleur heeft.<br/>            Lezen/schrijven **bool**. |
| [`has_series_lines`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Waar als de grafiek serielijnen heeft. Toegepast op gestapelde balk- en OfPie-grafieken.<br/>            Lezen/schrijven **bool**. |
| [`hi_low_lines_format`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Specificeert het HiLowLines-formaat.<br/>            HiLowLines toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose grafiektypen. |
| [`bubble_size_scale`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 % van de standaardgrootte liggen).<br/>            Lezen/schrijven **int**. |
| [`pie_split_custom_points`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | De aangepaste splitsingsinformatie voor een taart-in-taart- of balk-in-taart-grafiek met een aangepaste splitsing.<br/>            Bevat datapunten die in de tweede taart of balk van een taart-in-taart- of balk-in-taart-grafiek moeten worden getekend.<br/>            Alleen-lezen [`PieSplitCustomPointCollection`](/slides/python-net/nl/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/chart/) | Retourneert de bovenliggende grafiek.<br/>            Alleen-lezen [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Haalt het element op op de opgegeven index.

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Opmerkingen

1) Zie de samenvatting en opmerkingen voor de klasse ChartSeriesGroupCollection en de enumeratie CombinableSeriesTypesGroup.
2) Een groep series bevat enkele serie-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep (“series group properties”). “Series group properties” in de klasse ChartSeriesGroup is lezen/schrijven. Elke “series group properties” kan een alleen-lezen projectie hebben in de klasse ChartSeries.

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)