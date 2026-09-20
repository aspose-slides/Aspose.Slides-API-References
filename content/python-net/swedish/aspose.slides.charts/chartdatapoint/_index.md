---
title: ChartDataPoint class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klass

Representerar serie-datapunkt.

Typen ChartDataPoint exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`x_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Skrivskyddad [`IStringOrDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Skrivskyddad [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Skrivskyddad [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Skrivskyddad [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/size_value/) | Returnerar storleksvärdet för diagramdatapunkt.<br/>            Används med Treemap- och Sunburst-diagram.<br/>            Skrivskyddad [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/color_value/) | Returnerar färgvärdet för diagramdatapunkt.<br/>            Används med kart-diagram.<br/>            Skrivskyddad [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Representerar serie-felstaplarvärden när typ är Custom.<br/>            Skrivskyddad [`IErrorBarsCustomValues`](/slides/python-net/sv/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Skrivskyddad [`IDataLabel`](/slides/python-net/sv/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Anger att bubblorna har en 3-D-effekt tillämpad.<br/>            Läs/skriv **bool**. |
| [`explosion`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/explosion/) | Anger hur mycket datapunkten ska flyttas från mitten av pajen.<br/>            Läs/skriv **int**. |
| [`format`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/format/) | Representerar formateringsegenskaperna.<br/>            Läs/skriv [`IFormat`](/slides/python-net/sv/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/marker/) | Anger en datamarkör.<br/>            Skrivskyddad [`IMarker`](/slides/python-net/sv/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/set_as_total/) | Ställer in datapunkt som total. Endast tillämpad för Waterfall-serietyp. |
| [`related_legend_entry`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Egenskaper för motsvarande legendpost när diagramtyp är någon av följande:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Skrivskyddad [`ILegendEntryProperties`](/slides/python-net/sv/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/data_point_levels/) | Returnerar behållare för datapunktsnivåer. Tillämpars för Treeamp- och Sunburst-serier.<br/>            Indexering av datapunktsnivåer är nollbaserad. |
| [`index`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Anger att datapunkten ska invertera sina färger om värdet är negativt.<br/>            Läs/skriv **bool**. |
| [`actual_x`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/actual_x/) | Anger faktiskt x-läge (vänster) för diagramelementet relativt diagrammets övre vänstra hörn.<br/>            Anropa metoden IChart.ValidateChartLayout() innan du får faktiska värden.<br/>            Läs **float**. |
| [`actual_y`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/actual_y/) | Anger faktiskt övre läge för diagramelementet relativt diagrammets övre vänstra hörn.<br/>            Anropa metoden IChart.ValidateChartLayout() innan du får faktiska värden.<br/>            Läs **float**. |
| [`actual_width`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/actual_width/) | Anger faktisk bredd för diagramelementet. Anropa metoden IChart.ValidateChartLayout() innan du får faktiska värden.<br/>            Läs **float**. |
| [`actual_height`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/actual_height/) | Anger faktisk höjd för diagramelementet. Anropa metoden IChart.ValidateChartLayout() innan du får faktiska värden.<br/>            Läs **float**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`remove(self)`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/remove/#) | Tar bort DataPoint från diagramserie. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Returnerar en automatisk färg för datapunkt baserat på serie-index, datapunkt-index, ParentSeriesGroup.IsColorVaried-egenskapen och diagramstil.<br/>            Denna färg används som standard om FillType är NotDefined. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)