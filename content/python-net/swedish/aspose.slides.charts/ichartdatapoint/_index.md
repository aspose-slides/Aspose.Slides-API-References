---
title: IChartDataPoint class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint klass

Representerar en seriedatapunkt.

Typen IChartDataPoint exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`x_value`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/x_value/) | Returnerar x-värdet för diagramdatapunkt.<br/>            Läs-endast [`IStringOrDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/y_value/) | Returnerar y-värdet för diagramdatapunkt.<br/>            Läs-endast [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/bubble_size/) | Returnerar bubbelstorleken för diagramdatapunkt.<br/>            Läs-endast [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/value/) | Returnerar värdet för diagramdatapunkt.<br/>            Läs-endast [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/size_value/) | Returnerar storleksvärdet för diagramdatapunkt.<br/>            Används med Treemap- och Sunburst-diagram. <br/>            Läs-endast [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/color_value/) | Returnerar färgvärdet för diagramdatapunkt.<br/>            Används med kartdiagram. <br/>            Läs-endast [`IDoubleChartValue`](/slides/python-net/sv/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Representerar seriens felstaplarvärden i fall av Custom-värdetyp.<br/>            Läs-endast [`IErrorBarsCustomValues`](/slides/python-net/sv/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/label/) | Representerar etiketten för diagramdatapunkt.<br/>            Läs-endast [`IDataLabel`](/slides/python-net/sv/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Anger att bubblorna har en 3-D-effekt applicerad.<br/>            Läs-skriv **bool**. |
| [`explosion`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/explosion/) | Anger hur mycket datapunkten ska flyttas från mitten av pajen.<br/>            Läs-skriv **int**. |
| [`format`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/format/) | Representerar formateringsegenskaperna.<br/>            Läs-skriv [`IFormat`](/slides/python-net/sv/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/marker/) | Anger en datamarkör.<br/>            Läs-endast [`IMarker`](/slides/python-net/sv/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Egenskaper för motsvarande förklaringspost i fall av diagramtyp från följande lista:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Läs-endast [`ILegendEntryProperties`](/slides/python-net/sv/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/set_as_total/) | Ställer in datapunkten som total. Tillämpas endast för Waterfall-serietyp. |
| [`invert_if_negative`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Anger att datapunkten ska invertera sina färger om värdet är negativt.<br/>            Läs-skriv **bool**. |
| [`data_point_levels`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Returnerar behållaren för datapunktnivåer. Tillämpas för Treeamp- och Sunburst-serier.<br/>            Indexering av datapunktnivåer är nollbaserad. |
| [`index`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/index/) | Bestämmer vilken av förälderns barnsamling denna datapunkt gäller för.<br/>            Läs **int**. |
| [`actual_x`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`remove(self)`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/remove/#) | Tar bort DataPoint från diagramserie. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Returnerar en automatisk färg för datapunkt baserat på serieindex, datapunktindex, ParentSeriesGroup.IsColorVaried-egenskapen och diagramstil. <br/>            Denna färg används som standard om FillType är lika med NotDefined. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)