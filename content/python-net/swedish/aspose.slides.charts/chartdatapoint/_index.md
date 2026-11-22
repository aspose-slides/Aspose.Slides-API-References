---
title: ChartDataPoint class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klass

Representerar en seriedatapunkt.

ChartDataPoint-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`x_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Endast läsning [`IStringOrDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Endast läsning [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Endast läsning [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Endast läsning [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/size_value/) | Returnerar storleksvärdet för diagramdatapunkt.<br/>            Används med Treemap- och Sunburst-diagram. <br/>            Endast läsning [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/color_value/) | Returnerar färgvärdet för diagramdatapunkt.<br/>            Används med kartdiagram. <br/>            Endast läsning [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Representerar seriens felstaplarvärden vid anpassad värdetyp.<br/>            Endast läsning [`IErrorBarsCustomValues`](/slides/python-net/sv/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Endast läsning [`IDataLabel`](/slides/python-net/sv/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Anger att bubblorna har en 3-D-effekt tillämpad.<br/>            Läs/skriv **bool**. |
| [`explosion`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/explosion/) | Anger hur mycket datapunkten ska flyttas från mitten av pajen.<br/>            Läs/skriv **int**. |
| [`format`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/format/) | Representerar formateringsegenskaperna.<br/>            Läs/skriv [`IFormat`](/slides/python-net/sv/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/marker/) | Anger en datamarkör.<br/>            Endast läsning [`IMarker`](/slides/python-net/sv/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/set_as_total/) | Ställer in datapunkten som total. Tillämpas endast för Waterfall-serietyp. |
| [`related_legend_entry`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Egenskaper för motsvarande legendpost om diagramtyp är någon av följande:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Endast läsning [`ILegendEntryProperties`](/slides/python-net/sv/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/data_point_levels/) | Returnerar behållaren för datapunktnivåer. Tillämpas för Treeamp- och Sunburst-serier.<br/>            Indexering av datapunktnivåer är nollbaserad. |
| [`index`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Anger att datapunkten ska invertera sina färger om värdet är negativt.<br/>            Läs/skriv **bool**. |
| [`cached_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/cached_value/) | Hämtar det cachade värdet för en diagramdatapunkt.<br/>            Endast läsning [`ICachedChartValue`](/slides/python-net/sv/aspose.slides.charts/icachedchartvalue). |
| [`cached_x_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/cached_x_value/) | Hämtar det cachade X-värdet för en diagramdatapunkt.<br/>            Endast läsning [`ICachedChartValue`](/slides/python-net/sv/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/cached_y_value/) | Hämtar det cachade Y-värdet för en diagramdatapunkt.<br/>            Endast läsning [`ICachedChartValue`](/slides/python-net/sv/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/cached_bubble_size/) | Hämtar den cachade bubbla-storleken för en diagramdatapunkt.<br/>            Endast läsning [`ICachedChartValue`](/slides/python-net/sv/aspose.slides.charts/icachedchartvalue). |
| [`actual_x`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/actual_x/) | Anger den faktiska x-platsen (vänster) för diagramelementet relativt diagrammets vänstra övre hörn.<br/>            Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. <br/>            Läs **float**. |
| [`actual_y`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/actual_y/) | Anger den faktiska toppen av diagramelementet relativt diagrammets vänstra övre hörn.<br/>            Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. <br/>            Läs **float**. |
| [`actual_width`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/actual_width/) | Anger den faktiska bredden på diagramelementet. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. <br/>            Läs **float**. |
| [`actual_height`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/actual_height/) | Anger den faktiska höjden på diagramelementet. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. <br/>            Läs **float**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`remove(self)`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/remove/#) | Tar bort DataPoint från diagramserien. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/sv/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Returnerar en automatisk färg för datapunkten baserat på seriens index, datapunktens index, egenskapen ParentSeriesGroup.IsColorVaried och diagramstil.<br/>            Denna färg används som standard om FillType är lika med NotDefined. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)