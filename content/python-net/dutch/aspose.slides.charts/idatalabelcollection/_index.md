---
title: IDataLabelCollection class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection klasse

Stelt labels van een serie voor.

Het type IDataLabelCollection bevat de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Retourneert het standaardformaat van alle data labels in de collectie.<br/>            Alleen-lezen [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Stelt het opmaak van de leidende lijnen van data labels voor.<br/>             Alleen-lezen [`IChartLinesFormat`](/slides/python-net/nl/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/is_visible/) | False betekent dat het data label standaard niet zichtbaar is (en dus alle <br/>            Show*-flags (ShowValue, ...) van de eigenschap DefaultDataLabelFormat false zijn).<br/>            Alleen-lezen **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Haalt het aantal zichtbare data labels op in de collectie.<br/>            Alleen-lezen **int**. |
| [`count`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/count/) | Haalt het totale aantal data labels op in de collectie.<br/>            Alleen-lezen **int**. |
| [`parent_series`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/parent_series/) | Retourneert de bovenliggende grafiekreeks.<br/>            Alleen-lezen [`IChartSeries`](/slides/python-net/nl/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Haalt het standaardvormtype voor data labels op of stelt het in.<br/>             Retourneert [`ShapeType.NOT_DEFINED`](/slides/python-net/nl/aspose.slides/shapetype/NOT_DEFINED) als er geen vorm is gedefinieerd. |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Haalt het data label op voor het datapunt met de opgegeven index.

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`hide(self)`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/hide/#) | Maak het data label standaard verborgen door alle Show*-flags (ShowValue, ...) van de <br/>            eigenschap DefaultDataLabelFormat op false te zetten.<br/>            IsVisible zal daarna false zijn. |
| [`index_of(self, value)`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Retourneert een index van de gespecificeerde DataLabel in de collectie. |


### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)