---
title: DataLabel class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabel/
---
## DataLabel sınıfı

Seri etiketlerini temsil eder.

DataLabel türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Constructor | Description |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/tr/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Creates a new instance of DataLabel class. |

## Özellikler

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/datalabel/chart/) | Returns the parent chart.<br/>            Yalnızca okunabilir [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/tr/aspose.slides.charts/datalabel/is_visible/) | False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false).<br/>            Yalnızca okunabilir **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/tr/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Can contain a rich formatted text. If this property is not None then this <br/>            formatted text value overrides auto-generated text of data label.<br/>            Auto-generated text of data label means text that is managed by ShowSeriesName, <br/>            ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property.<br/>            Yalnızca okunabilir [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/tr/aspose.slides.charts/datalabel/text_format/) | Returns text format.<br/>            Yalnızca okunabilir [`IChartTextFormat`](/slides/python-net/tr/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/tr/aspose.slides.charts/datalabel/x/) | Returns or sets the x coordinate of a title as a fraction of the width of the chart.<br/>            Okunur/yazılır **float**. |
| [`y`](/slides/python-net/tr/aspose.slides.charts/datalabel/y/) | Returns or sets the y coordinate of a title as a fraction of the height of the chart.<br/>            Okunur/yazılır **float**. |
| [`width`](/slides/python-net/tr/aspose.slides.charts/datalabel/width/) | Returns or sets the width of a title as a fraction of the width of the chart.<br/>            Okunur/yazılır **float**. |
| [`height`](/slides/python-net/tr/aspose.slides.charts/datalabel/height/) | Returns or sets the height of a title as a fraction of the height of the chart.<br/>            Okunur/yazılır **float**. |
| [`right`](/slides/python-net/tr/aspose.slides.charts/datalabel/right/) | Right.<br/>            Yalnızca okunabilir **float**. |
| [`bottom`](/slides/python-net/tr/aspose.slides.charts/datalabel/bottom/) | Bottom.<br/>            Yalnızca okunabilir **float**. |
| [`data_label_format`](/slides/python-net/tr/aspose.slides.charts/datalabel/data_label_format/) | Returns data label format.<br/>            Yalnızca okunabilir [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/tr/aspose.slides.charts/datalabel/value_from_cell/) | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |
| [`actual_x`](/slides/python-net/tr/aspose.slides.charts/datalabel/actual_x/) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Okunur **float**. |
| [`actual_y`](/slides/python-net/tr/aspose.slides.charts/datalabel/actual_y/) | Specifies actual top of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Okunur **float**. |
| [`actual_width`](/slides/python-net/tr/aspose.slides.charts/datalabel/actual_width/) | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Okunur **float**. |
| [`actual_height`](/slides/python-net/tr/aspose.slides.charts/datalabel/actual_height/) | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Okunur **float**. |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/datalabel/presentation/) |  |

## Yöntemler

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/tr/aspose.slides.charts/datalabel/hide/#) | Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state.<br/>            IsVisible will be false after this. |
| [`get_actual_label_text(self)`](/slides/python-net/tr/aspose.slides.charts/datalabel/get_actual_label_text/#) | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/tr/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Initialize TextFrameForOverriding with the text in paramener "text".<br/>            If TextFrameForOverriding is already initialized then simply changes its text. |


### İlgili Bilgiler
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)