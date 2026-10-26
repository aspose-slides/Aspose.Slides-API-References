---
title: IDataLabelCollection class
second_title: Aspose.Slides pro Python přes .NET API
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection třída

Reprezentuje popisky řady.

Typ IDataLabelCollection vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Vrací výchozí formát všech popisků dat v kolekci.<br/>            Pouze pro čtení [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Reprezentuje formát linkových čar popisků dat.<br/>            Pouze pro čtení [`IChartLinesFormat`](/slides/python-net/cs/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/is_visible/) | False znamená, že popisek dat není ve výchozím nastavení viditelný (a tak všechny <br/>            příznaky Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat jsou false).<br/>            Pouze pro čtení **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Získá počet viditelných popisků dat v kolekci.<br/>            Pouze pro čtení **int**. |
| [`count`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/count/) | Získá počet všech popisků dat v kolekci.<br/>            Pouze pro čtení **int**. |
| [`parent_series`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/parent_series/) | Vrací nadřazenou sérii grafu.<br/>            Pouze pro čtení [`IChartSeries`](/slides/python-net/cs/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Získá popisek dat pro datový bod se zadaným indexem.

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`hide(self)`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/hide/#) | Zpřístupní popisek dat skrytý ve výchozím nastavení nastavením všech příznaků Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat do stavu false.<br/>            IsVisible bude po tomto nastavení false. |
| [`index_of(self, value)`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Vrací index zadaného DataLabel v kolekci. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)