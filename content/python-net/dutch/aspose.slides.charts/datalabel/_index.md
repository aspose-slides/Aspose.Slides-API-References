---
title: DataLabel class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/datalabel/
---
## DataLabel klasse

Stelt een reekslabels voor.

Het DataLabel-type geeft de volgende leden weer:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/nl/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Creates a new instance of DataLabel class. |

## Eigenschappen

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/datalabel/chart/) | Retourneert de bovenliggende grafiek.<br/>            Alleen-lezen [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/nl/aspose.slides.charts/datalabel/is_visible/) | False betekent dat data label niet zichtbaar is (en dus alle Show*-flags (ShowValue, ...) false zijn).<br/>            Alleen-lezen **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/nl/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet None is, dan overschrijft deze <br/>            opgemaakte tekstwaarde de automatisch gegenereerde tekst van het data label.<br/>            Automatisch gegenereerde tekst van het data label betekent tekst die wordt beheerd door ShowSeriesName, <br/>            ShowValue, ... eigenschappen en wordt opgemaakt met de TextFormatManager.TextFormat eigenschap.<br/>            Alleen-lezen [`ITextFrame`](/slides/python-net/nl/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/nl/aspose.slides.charts/datalabel/text_format/) | Retourneert tekstindeling.<br/>            Alleen-lezen [`IChartTextFormat`](/slides/python-net/nl/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/nl/aspose.slides.charts/datalabel/x/) | Retourneert of stelt de x-coördinaat van een titel in als een fractie van de breedte van de grafiek.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides.charts/datalabel/y/) | Retourneert of stelt de y-coördinaat van een titel in als een fractie van de hoogte van de grafiek.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides.charts/datalabel/width/) | Retourneert of stelt de breedte van een titel in als een fractie van de breedte van de grafiek.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides.charts/datalabel/height/) | Retourneert of stelt de hoogte van een titel in als een fractie van de hoogte van de grafiek.<br/>            Lezen/Schrijven **float**. |
| [`right`](/slides/python-net/nl/aspose.slides.charts/datalabel/right/) | Rechts.<br/>            Alleen-lezen **float**. |
| [`bottom`](/slides/python-net/nl/aspose.slides.charts/datalabel/bottom/) | Onder.<br/>            Alleen-lezen **float**. |
| [`data_label_format`](/slides/python-net/nl/aspose.slides.charts/datalabel/data_label_format/) | Retourneert data label-indeling.<br/>            Alleen-lezen [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/nl/aspose.slides.charts/datalabel/value_from_cell/) | Haalt op of stelt werkboekgegevenscel in. Toegepast als de eigenschap IDataLabelFormat.ShowLabelValueFromCell true is. |
| [`actual_x`](/slides/python-net/nl/aspose.slides.charts/datalabel/actual_x/) | Specificeert de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek.<br/>            Roep methode IChart.ValidateChartLayout() aan voordat je werkelijke waarden krijgt. <br/>            Lezen **float**. |
| [`actual_y`](/slides/python-net/nl/aspose.slides.charts/datalabel/actual_y/) | Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek.<br/>            Roep methode IChart.ValidateChartLayout() aan voordat je werkelijke waarden krijgt. <br/>            Lezen **float**. |
| [`actual_width`](/slides/python-net/nl/aspose.slides.charts/datalabel/actual_width/) | Specificeert de werkelijke breedte van het grafiekelement. Roep methode IChart.ValidateChartLayout() aan voordat je werkelijke waarden krijgt. <br/>            Lezen **float**. |
| [`actual_height`](/slides/python-net/nl/aspose.slides.charts/datalabel/actual_height/) | Specificeert de werkelijke hoogte van het grafiekelement. Roep methode IChart.ValidateChartLayout() aan voordat je werkelijke waarden krijgt. <br/>            Lezen **float**. |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/datalabel/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/nl/aspose.slides.charts/datalabel/hide/#) | Maakt data label verborgen door alle Show*-flags (ShowValue, ...) op de valse toestand te zetten.<br/>            IsVisible zal daarna false zijn. |
| [`get_actual_label_text(self)`](/slides/python-net/nl/aspose.slides.charts/datalabel/get_actual_label_text/#) | Retourneert de werkelijke labeltekst op basis van de instellingen van DataLabelFormat of de waarde van TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/nl/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Initialiseert TextFrameForOverriding met de tekst in parameter "text".<br/>            Als TextFrameForOverriding al is geïnitialiseerd, wordt de tekst eenvoudig gewijzigd. |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)