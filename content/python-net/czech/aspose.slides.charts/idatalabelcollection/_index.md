---
title: IDataLabelCollection class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection třída

Reprezentuje popisky řady.

Typ IDataLabelCollection poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Vrací výchozí formát všech popisků dat v kolekci.<br/>            Pouze ke čtení [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Zastupuje formát vodících čar popisků dat.<br/>             Pouze ke čtení [`IChartLinesFormat`](/slides/python-net/cs/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/is_visible/) | False znamená, že popisek dat není ve výchozím nastavení viditelný (a tak všechny <br/>            Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat jsou false).<br/>            Pouze ke čtení **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Získá počet viditelných popisků dat v kolekci.<br/>            Pouze ke čtení **int**. |
| [`count`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/count/) | Získá počet všech popisků dat v kolekci.<br/>            Pouze ke čtení **int**. |
| [`parent_series`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/parent_series/) | Vrací nadřazenou sérii grafu.<br/>            Pouze ke čtení [`IChartSeries`](/slides/python-net/cs/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Získá nebo nastaví výchozí typ tvaru pro popisky dat.<br/>             Vrací [`ShapeType.NOT_DEFINED`](/slides/python-net/cs/aspose.slides/shapetype/NOT_DEFINED), pokud není definován žádný tvar. |
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
| [`hide(self)`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/hide/#) | Skryje popisek dat ve výchozím nastavení nastavením všech Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat do stavu false.<br/>            IsVisible bude po tomto nastavení false. |
| [`index_of(self, value)`](/slides/python-net/cs/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Vrací index zadaného DataLabel v kolekci. |


### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)