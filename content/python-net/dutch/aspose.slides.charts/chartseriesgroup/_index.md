---
title: ChartSeriesGroup class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasse

Represents group of series.

The ChartSeriesGroup type exposes the following members:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`type`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/type/) | Geeft een type van deze seriesgroep terug.<br/>            Alleen-lezen [`CombinableSeriesTypesGroup`](/slides/python-net/nl/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Geeft aan of de series van deze groep worden weergegeven op een secundaire as.<br/>            Alleen-lezen **bool**. |
| [`series`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/series/) | Geeft een verzameling series terug.<br/>            Alleen-lezen [`IChartSeriesReadonlyCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Biedt toegang tot op/ neer-balken van een lijn- of aandelengrafiek.<br/>            Alleen-lezen [`IUpDownBarsManager`](/slides/python-net/nl/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/gap_width/) | Haalt de ruimte tussen balk- of kolomclusters op of stelt deze in, als een percentage van de breedte van de balk of kolom.<br/>            De waarde moet tussen 0 en 500 liggen.<br/>            Lezen/schrijven **int**. |
| [`gap_depth`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/gap_depth/) | Haalt de afstand tussen dataseries in een 3D-grafiek op of stelt deze in, als een percentage van de markerbreedte.<br/>            De waarde moet tussen 0 en 500 liggen.<br/>            Lezen/schrijven **int**. |
| [`first_slice_angle`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Haalt de hoek van het eerste part van een taart- of donutsgrafiek op of stelt deze in, <br/>            in graden (met de klok mee vanaf boven, van 0 tot 360 graden).<br/>            Lezen/schrijven **int**. |
| [`doughnut_hole_size`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Bepaalt de grootte van het gat in een donutsgrafiek (kan tussen 0 en 90 procent <br/>            van de grootte van het plotgebied zijn).<br/>            Lezen/schrijven **int**. |
| [`overlap`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/overlap/) | Bepaalt hoeveel balken en kolommen overlappen in 2-D grafieken, als een percentage (van -100% tot 100%).<br/>             - -100%: Maximale afstand (balken zijn volledig gescheiden).<br/>             - 0%: Balken staan naast elkaar zonder overlapping of afstand.<br/>             - 100%: Maximale overlapping (balken overlappen volledig).<br/>             Deze eigenschap is lezen/schrijven **int**. |
| [`second_pie_size`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Bepaalt de grootte van de tweede taart of balk van een taart-in-taart grafiek of <br/>            een balk-in-taart grafiek, als een percentage van de grootte van de eerste taart (kan <br/>            tussen 5 en 200 procent liggen).<br/>            Lezen/schrijven **int**. |
| [`bubble_size_representation`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Bepaalt hoe de bubbelformaatwaarden worden weergegeven in de bubbelgrafiek.<br/>            Lezen/schrijven [`BubbleSizeRepresentationType`](/slides/python-net/nl/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Bepaalt een waarde die gebruikt wordt om te bepalen welke gegevenspunten <br/>            in de tweede taart of balk van een taart-in-taart of balk-in-taart grafiek zitten. <br/>            Wordt samen met de eigenschap PieSplitBy gebruikt.<br/>            Lezen/schrijven **float**. |
| [`pie_split_by`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Bepaalt hoe te bepalen welke gegevenspunten in de tweede taart of balk <br/>            van een taart-in-taart of balk-in-taart grafiek zitten.<br/>            Lezen/schrijven [`PieSplitType`](/slides/python-net/nl/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Bepaalt dat elke datamarker in de series een andere kleur heeft.<br/>            Lezen/schrijven **bool**. |
| [`has_series_lines`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Waar als de grafiek serieslijnen heeft. Toegepast op gestapelde balken en OfPie grafieken.<br/>            Lezen/schrijven **bool**. |
| [`hi_low_lines_format`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Bepaalt het HiLowLines-formaat. <br/>            HiLowLines wordt toegepast met de grafiektype HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Bepaalt de schaalfactor voor de bubbelgrafiek (kan <br/>            tussen 0 en 300 procent van de standaardgrootte liggen).<br/>            Lezen/schrijven **int**. |
| [`pie_split_custom_points`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | De aangepaste split-informatie voor een taart-in-taart of balk-in-taart grafiek met een aangepaste split.<br/>            Bevat gegevenspunten die getekend moeten worden in de tweede taart of balk in een taart-in-taart of <br/>            balk-in-taart grafiek.<br/>            Alleen-lezen [`PieSplitCustomPointCollection`](/slides/python-net/nl/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/chart/) | Geeft de bovenliggende grafiek terug.<br/>            Alleen-lezen [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Haalt het element op op de opgegeven index.

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Opmerkingen

1) Zie de samenvatting en opmerkingen voor de ChartSeriesGroupCollection klasse en de CombinableSeriesTypesGroup enum.  
2) Een groep series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep ('series groep eigenschappen').  
"Series group properties" in de ChartSeriesGroup klasse is lezen/schrijven.  
Elke "series group properties" kan een alleen-lezen projectie hebben in de ChartSeries klasse.

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)