---
title: DataLabelCollection class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection třída

Represents a series labels.

The DataLabelCollection type exposes the following members:

## Vlastnosti

| Property | Popis |
| :- | :- |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/chart/) | Vrací nadřazený graf.<br/>            Pouze pro čtení [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/is_visible/) | False znamená, že popisek dat není ve výchozím nastavení viditelný (a proto jsou všechny <br/>            Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat nastaveny na false).<br/>            Pouze pro čtení **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Vrací počet viditelných popisků dat v kolekci.<br/>            Pouze pro čtení **int**. |
| [`count`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/count/) | Vrací počet všech popisků dat v kolekci.<br/>            Pouze pro čtení **int**. |
| [`default_data_label_format`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Vrací výchozí formát popisku dat.<br/>            Pouze pro čtení [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Reprezentuje formát čar spojujících popisky dat.<br/>             Pouze pro čtení [`IChartLinesFormat`](/slides/python-net/cs/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/parent_series/) | Vrací nadřazenou sérii.<br/>            Pouze pro čtení [`IChartSeries`](/slides/python-net/cs/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | Vrací nebo nastavuje výchozí typ tvaru pro popisky dat.<br/>             Vrací [`ShapeType.NOT_DEFINED`](/slides/python-net/cs/aspose.slides/shapetype/NOT_DEFINED) pokud není žádný tvar definován. |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/presentation/) |  |

Vrací popisek dat pro datový bod se zadaným indexem.

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`hide(self)`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/hide/#) | Učiní popisek dat ve výchozím nastavení skrytým nastavením všech Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na stav false.<br/>            IsVisible bude po tomto nastaveno na false. |
| [`index_of(self, value)`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Vrací index zadaného DataLabel v kolekci. |


### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)