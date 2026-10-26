---
title: ChartDataPoint
second_title: Aspose.Sildes .NET API hivatkozás
description: A sorozat adatpontját képviseli.
type: docs
weight: 1330
url: /hu/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint osztály

Represents series data point.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Meghatározza a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Meghatározza a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Meghatározza a diagram elem tényleges x helyzetét (bal) a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Meghatározza a diagram elem tényleges tetejét a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Visszaadja a diagram adatpont színértékét. Térképes diagramoknál használatos. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Visszaadja az adatpont szintek tárolóját. Alkalmazható Treeamp és Sunburst sorozatoknál. Az adatpont szintek indexelése nullától indul. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Sorozat hibarajz értékeket képviseli egyéni értéktípus esetén. Csak olvasható [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Meghatározza, hogy mennyivel legyen az adatpont eltolva a kördiagram középpontjától. Olvasás/írás Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Képviseli a formázási tulajdonságokat. Olvasás/írás [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Meghatározza, hogy az adatpont negatív érték esetén megfordítsa színeit. Olvasás/írás Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Meghatározza, hogy a buborékokra 3D effektus legyen alkalmazva. Olvasás/írás Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Csak olvasható [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Meghatározza egy adatjelzőt. Csak olvasható [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | A megfelelő jelmagyarázat bejegyzés tulajdonságai az alábbi diagramtípusok esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Csak olvasható [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Az adatpontot összegként állítja be. Csak Waterfall sorozattípusnál alkalmazható. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Visszaadja a diagram adatpont méretértékét. Treemap és Sunburst diagramoknál használatos. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Csak olvasható [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Visszaad egy automatikus színt az adatponthoz, amely a sorozat indexén, az adatpont indexén, a ParentSeriesGroup.IsColorVaried tulajdonságon és a diagram stílusán alapul. Ez a szín lesz alapértelmezés szerint használva, ha a FillType NotDefined értékű. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Eltávolítja a DataPoint-ot a diagram sorozatból. |

### Lásd még

* interfész [IChartDataPoint](../ichartdatapoint)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->