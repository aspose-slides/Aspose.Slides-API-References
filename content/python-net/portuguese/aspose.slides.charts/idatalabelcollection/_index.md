---
title: IDataLabelCollection class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection classe

Representa os rótulos de uma série.

O tipo IDataLabelCollection expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Returns default format of all data labels in the collection.<br/>            Read-only [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Represents data labels leader lines format.<br/>             Read-only [`IChartLinesFormat`](/slides/python-net/pt/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/is_visible/) | False means that data label is not visible by default (and so all <br/>            Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false).<br/>            Read-only **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Gets the number of visible data labels in the collection.<br/>            Read-only **int**. |
| [`count`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/count/) | Gets the number of all data labels in the collection.<br/>            Read-only **int**. |
| [`parent_series`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/parent_series/) | Returns parent chart series.<br/>            Read-only [`IChartSeries`](/slides/python-net/pt/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Gets or sets the default shape type for data labels.<br/>             Returns [`ShapeType.NOT_DEFINED`](/slides/python-net/pt/aspose.slides/shapetype/NOT_DEFINED) if no shape is defined. |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Obtém o rótulo de dados para o ponto de dados com o índice especificado.

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`hide(self)`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/hide/#) | Make data label hidden by default by setting all Show*-flags (ShowValue, ...) of the <br/>            DefaultDataLabelFormat property to false state.<br/>            IsVisible will be false after this. |
| [`index_of(self, value)`](/slides/python-net/pt/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Returns an index of the specified DataLabel in the collection. |

### Ver Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)