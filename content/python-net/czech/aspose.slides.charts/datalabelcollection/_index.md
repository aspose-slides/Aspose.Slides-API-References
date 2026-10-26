---
title: DataLabelCollection class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection třída

Představuje popisky řady.

Typ DataLabelCollection vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/chart/) | Vrací nadřazený graf.<br/>            Pouze pro čtení [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/is_visible/) | False znamená, že popisek dat není ve výchozím nastavení viditelný (a proto jsou všechny <br/>            Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat nastaveny na false).<br/>            Pouze pro čtení **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Vrací počet viditelných popisků dat ve sbírce.<br/>            Pouze pro čtení **int**. |
| [`count`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/count/) | Vrací počet všech popisků dat ve sbírce.<br/>            Pouze pro čtení **int**. |
| [`default_data_label_format`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Vrací výchozí formát popisku dat.<br/>            Pouze pro čtení [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Reprezentuje formát vodicích čar popisků dat.<br/>             Pouze pro čtení [`IChartLinesFormat`](/slides/python-net/cs/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/parent_series/) | Vrací nadřazenou sérii.<br/>            Pouze pro čtení [`IChartSeries`](/slides/python-net/cs/aspose.slides.charts/ichartseries). |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/presentation/) |  |

Vrací popisek dat pro datový bod se zadaným indexem.

## Indexér

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/hide/#) | Skryje popisek dat ve výchozím nastavení nastavením všech Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat do stavu false.<br/>            IsVisible bude po tomto nastavení false. |
| [`index_of(self, value)`](/slides/python-net/cs/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Vrací index zadaného DataLabel ve sbírce. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)