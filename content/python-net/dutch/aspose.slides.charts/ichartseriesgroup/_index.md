---
title: IChartSeriesGroup class
second_title: Aspose.Slides voor Python via .NET API-referentie
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
| [`type`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/type/) | Retourneert een type van deze serie-groep.<br/>            Alleen-lezen [`CombinableSeriesTypesGroup`](/slides/python-net/nl/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Geeft aan of series van deze groep worden weergegeven op een secundaire as.<br/>            Alleen-lezen **bool**. |
| [`series`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/series/) | Retourneert een alleen-lezen collectie van diagram-series.<br/>            Alleen-lezen [`IChartSeriesReadonlyCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Biedt toegang tot op/om-balken van lijndiagram- of aandelendiagram.<br/>            Alleen-lezen [`IUpDownBarsManager`](/slides/python-net/nl/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/gap_width/) | Haalt op of stelt de ruimte tussen balk- of kolom-clusters in, als een percentage van de balk- of kolombreedte.<br/>            De waarde moet tussen 0 en 500 liggen.<br/>            Lezen/Schrijven **int**. |
| [`gap_depth`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Haalt op of stelt de afstand tussen gegevens-series in een 3D-diagram in, als een percentage van de markerbreedte.<br/>            De waarde moet tussen 0 en 500 liggen.<br/>            Lezen/Schrijven **int**. |
| [`first_slice_angle`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Haalt op of stelt de hoek van het eerste taart- of donut-diagramsegment in,<br/>            in graden (met de klok mee vanaf boven, van 0 tot 360 graden).<br/>            Lezen/Schrijven **int**. |
| [`is_color_varied`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Specificeert dat elke datamarker in de serie een andere kleur heeft.<br/>            Lezen/Schrijven **bool**. |
| [`has_series_lines`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Waar als het diagram serie-lijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen.<br/>            Lezen/Schrijven **bool**. |
| [`overlap`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/overlap/) | Specificeert hoeveel balken en kolommen overlappen op 2-D-diagrammen, als een percentage (van -100% tot 100%).<br/>             - -100%: Maximale afstand (balken zijn volledig gescheiden).<br/>             - 0%: Balken worden naast elkaar geplaatst zonder overlap of afstand.<br/>             - 100%: Maximale overlap (balken overlappen volledig elkaar).<br/>             Deze eigenschap is Lezen/Schrijven **int**. |
| [`second_pie_size`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Specificeert de grootte van de tweede taart of balk van een pie-of-pie-diagram of <br/>            een bar-of-pie-diagram, als een percentage van de grootte van de eerste taart (kan <br/>            tussen 5 en 200 procent liggen).<br/>            Lezen/Schrijven **int**. |
| [`pie_split_position`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten <br/>            zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-diagram. <br/>            Wordt samen met de eigenschap PieSplitBy gebruikt.<br/>            Lezen/Schrijven **float**. |
| [`pie_split_by`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk <br/>            bevinden in een pie-of-pie- of bar-of-pie-diagram.<br/>            Lezen/Schrijven [`PieSplitType`](/slides/python-net/nl/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | De aangepaste split-informatie voor een pie-of-pie- of bar-of-pie-diagram met een aangepaste split.<br/>            Bevat gegevenspunten die getekend moeten worden in de tweede taart of balk in een pie-of-pie- of <br/>            bar-of-pie-diagram.<br/>            Alleen-lezen [`IPieSplitCustomPointCollection`](/slides/python-net/nl/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen).<br/>            Lezen/Schrijven **int**. |
| [`bubble_size_scale`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Specificeert de schaalfactor voor het bubbel-diagram (kan <br/>            tussen 0 en 300 procent van de standaardgrootte liggen).<br/>            Lezen/Schrijven **int**. |
| [`hi_low_lines_format`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Specificeert HiLowLines-formaat. <br/>            HiLowLines toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose diagramtypen. |
| [`bubble_size_representation`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Specificeert hoe de bubbelgroottwaarden worden weergegeven in het bubbel-diagram.<br/>            Lezen/Schrijven [`BubbleSizeRepresentationType`](/slides/python-net/nl/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Haalt het element op op de opgegeven index.

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Opmerkingen

1) Zie samenvatting en opmerkingen voor ChartSeriesGroupCollection klasse en CombinableSeriesTypesGroup enum.  
2) Groep van series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep ("series group properties").  
"Series group properties" in ChartSeriesGroup klasse is Lezen/Schrijven.  
Elk van "series group properties" kan een Alleen-lezen projectie hebben in ChartSeries klasse.

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)