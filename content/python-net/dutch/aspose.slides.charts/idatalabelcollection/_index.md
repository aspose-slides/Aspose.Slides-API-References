---
title: IDataLabelCollection class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection klasse

Stelt een serie labels voor.

Het IDataLabelCollection-type geeft de volgende leden weer:

## Eigenschappen

| Property | Beschrijving |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Retourneert het standaardformaat van alle data labels in de collectie.<br/>            Alleen-lezen [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Stelt het formaat van de leiderlijnen van data labels voor.<br/>             Alleen-lezen [`IChartLinesFormat`](/slides/python-net/nl/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/is_visible/) | False betekent dat data label standaard niet zichtbaar is (en dus alle <br/>            Show*-flags (ShowValue, ...) van de DefaultDataLabelFormat eigenschap false zijn).<br/>            Alleen-lezen **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Haalt het aantal zichtbare data labels in de collectie op.<br/>            Alleen-lezen **int**. |
| [`count`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/count/) | Haalt het totale aantal data labels in de collectie op.<br/>            Alleen-lezen **int**. |
| [`parent_series`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/parent_series/) | Retourneert de bovenliggende chart series.<br/>            Alleen-lezen [`IChartSeries`](/slides/python-net/nl/aspose.slides.charts/ichartseries). |
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
| [`hide(self)`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/hide/#) | Maak data label standaard verborgen door alle Show*-flags (ShowValue, ...) van de <br/>            DefaultDataLabelFormat eigenschap op false te zetten.<br/>            IsVisible zal daarna false zijn. |
| [`index_of(self, value)`](/slides/python-net/nl/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Retourneert een index van het opgegeven DataLabel in de collectie. |


### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)