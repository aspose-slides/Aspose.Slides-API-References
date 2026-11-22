---
title: DataLabel class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/datalabel/
---
## DataLabel classe

Representa rótulos de série.

O tipo DataLabel expõe os seguintes membros:

## Construtores

| Constructor | Description |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/pt/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Cria uma nova instância da classe DataLabel. |

## Propriedades

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/datalabel/chart/) | Returns the parent chart.<br/>            Somente leitura [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/pt/aspose.slides.charts/datalabel/is_visible/) | False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false).<br/>            Somente leitura **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/pt/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Can contain a rich formatted text. If this property is not None then this <br/>            formatted text value overrides auto-generated text of data label.<br/>            Auto-generated text of data label means text that is managed by ShowSeriesName, <br/>            ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property.<br/>            Somente leitura [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/pt/aspose.slides.charts/datalabel/text_format/) | Returns text format.<br/>            Somente leitura [`IChartTextFormat`](/slides/python-net/pt/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/pt/aspose.slides.charts/datalabel/x/) | Returns or sets the x coordinate of a title as a fraction of the width of the chart.<br/>            Leitura/Gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides.charts/datalabel/y/) | Returns or sets the y coordinate of a title as a fraction of the height of the chart.<br/>            Leitura/Gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides.charts/datalabel/width/) | Returns or sets the width of a title as a fraction of the width of the chart.<br/>            Leitura/Gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides.charts/datalabel/height/) | Returns or sets the height of a title as a fraction of the height of the chart.<br/>            Leitura/Gravação **float**. |
| [`right`](/slides/python-net/pt/aspose.slides.charts/datalabel/right/) | Right.<br/>            Somente leitura **float**. |
| [`bottom`](/slides/python-net/pt/aspose.slides.charts/datalabel/bottom/) | Bottom.<br/>            Somente leitura **float**. |
| [`data_label_format`](/slides/python-net/pt/aspose.slides.charts/datalabel/data_label_format/) | Returns data label format.<br/>            Somente leitura [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/pt/aspose.slides.charts/datalabel/value_from_cell/) | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |
| [`label_shape_type`](/slides/python-net/pt/aspose.slides.charts/datalabel/label_shape_type/) | Gets or sets the shape type of the data label.<br/>             Returns [`ShapeType.NOT_DEFINED`](/slides/python-net/pt/aspose.slides/shapetype/NOT_DEFINED) if no shape is defined. |
| [`actual_x`](/slides/python-net/pt/aspose.slides.charts/datalabel/actual_x/) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Leitura **float**. |
| [`actual_y`](/slides/python-net/pt/aspose.slides.charts/datalabel/actual_y/) | Specifies actual top of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Leitura **float**. |
| [`actual_width`](/slides/python-net/pt/aspose.slides.charts/datalabel/actual_width/) | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Leitura **float**. |
| [`actual_height`](/slides/python-net/pt/aspose.slides.charts/datalabel/actual_height/) | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Leitura **float**. |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/datalabel/presentation/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/pt/aspose.slides.charts/datalabel/hide/#) | Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state.<br/>            IsVisible will be false after this. |
| [`get_actual_label_text(self)`](/slides/python-net/pt/aspose.slides.charts/datalabel/get_actual_label_text/#) | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/pt/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Initialize TextFrameForOverriding with the text in paramener "text".<br/>            If TextFrameForOverriding is already initialized then simply changes its text. |


### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)