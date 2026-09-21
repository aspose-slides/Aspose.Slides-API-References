---
title: IChartSeriesGroup class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup klasse

Represents group of series.

The IChartSeriesGroup type exposes the following members:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`type`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/type/) | Retourneert een type van deze seriesgroep.<br/>            Alleen-lezen [`CombinableSeriesTypesGroup`](/slides/python-net/nl/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Geeft aan of series van deze groep worden weergegeven op de secundaire as.<br/>            Alleen-lezen **bool**. |
| [`series`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/series/) | Retourneert een alleen-lezen collectie van grafiekseries.<br/>            Alleen-lezen [`IChartSeriesReadonlyCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Biedt toegang tot up/down-balken van een Lijn- of Aandelen-grafiek.<br/>            Alleen-lezen [`IUpDownBarsManager`](/slides/python-net/nl/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/gap_width/) | Specificeert de ruimte tussen balk- of kolomcluster, als een percentage van de balk- of kolombreedte.<br/>            Lezen/schrijven **int**. |
| [`gap_depth`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensseries in een 3D-grafiek.<br/>            Lezen/schrijven **int**. |
| [`first_slice_angle`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Haalt op of stelt de hoek van het eerste taart- of donutscherp stuk in, <br/>            in graden (met de klok mee vanaf boven, van 0 tot 360 graden).<br/>            Lezen/schrijven **int**. |
| [`is_color_varied`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Specificeert dat elke gegevensmarker in de serie een andere kleur heeft.<br/>            Lezen/schrijven **bool**. |
| [`has_series_lines`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Waar als de grafiek serielijnen heeft. Toegepast op gestapelde balk- en OfPie-grafieken.<br/>            Lezen/schrijven **bool**. |
| [`overlap`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/overlap/) | Specificeert hoeveel balken en kolommen elkaar overlappen op 2-D-grafieken, als een percentage (van -100% tot 100%).<br/>             - -100%: Maximale afstand (balken zijn volledig gescheiden).<br/>             - 0%: Balken staan naast elkaar zonder overlapping of afstand.<br/>             - 100%: Maximale overlapping (balken overlappen volledig elkaar).<br/>             Deze eigenschap is lezen/schrijven **int**. |
| [`second_pie_size`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Specificeert de grootte van de tweede taart- of balk van een taart-in-taart-grafiek of <br/>            een balk-in-taart-grafiek, als een percentage van de grootte van de eerste taart (kan <br/>            tussen 5 en 200 procent liggen).<br/>            Lezen/schrijven **int**. |
| [`pie_split_position`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Specificeert een waarde die wordt gebruikt om te bepalen welke gegevenspunten <br/>            zich in de tweede taart of balk bevinden op een taart-in-taart- of balk-in-taart-grafiek. <br/>            Wordt gebruikt samen met de PieSplitBy-eigenschap.<br/>            Lezen/schrijven **float**. |
| [`pie_split_by`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden <br/>            op een taart-in-taart- of balk-in-taart-grafiek.<br/>            Lezen/schrijven [`PieSplitType`](/slides/python-net/nl/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | De aangepaste splitsingsinformatie voor een taart-in-taart- of balk-in-taart-grafiek met een aangepaste splitsing.<br/>            Bevat gegevenspunten die moeten worden getekend in de tweede taart of balk in een taart-in-taart- of <br/>            balk-in-taart-grafiek.<br/>            Alleen-lezen [`IPieSplitCustomPointCollection`](/slides/python-net/nl/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Specificeert de grootte van het gat in een donutsgrafiek (kan tussen 10 en 90 procent liggen <br/>            van de grootte van het plotgebied.).<br/>            Lezen/schrijven **int**. |
| [`bubble_size_scale`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Specificeert de schaalfactor voor de bubbelsgrafiek (kan <br/>            tussen 0 en 300 procent van de standaardgrootte liggen).<br/>            Lezen/schrijven **int**. |
| [`hi_low_lines_format`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Specificeert HiLowLines-indeling. <br/>            HiLowLines wordt toegepast met de charttypes HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Specificeert hoe de bubbelgroottewaarden worden weergegeven op de bubbelsgrafiek.<br/>            Lezen/schrijven [`BubbleSizeRepresentationType`](/slides/python-net/nl/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Haalt het element op op de opgegeven index.

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### Opmerkingen

1) Zie overzicht en opmerkingen voor de ChartSeriesGroupCollection klasse en de CombinableSeriesTypesGroup enum.  
2) Een groep series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor  
elke serie in de groep ("series groeps-eigenschappen").  
"Series groeps-eigenschappen" in de ChartSeriesGroup klasse is lezen/schrijven.  
Elke van de "series groeps-eigenschappen" kan een alleen-lezen projectie hebben in de ChartSeries klasse.

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)