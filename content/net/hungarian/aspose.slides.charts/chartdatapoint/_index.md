---
title: ChartDataPoint
second_title: Aspose.Sildes .NET API referenciája
description: Sorozat adatpontot képvisel.
type: docs
weight: 1310
url: /hu/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint osztály

Sorozat adatpontot képvisel.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Meghatározza a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Meghatározza a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Meghatározza a diagram elem tényleges x pozícióját (balra) a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Meghatározza a diagram elem tényleges tetejét a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Írásvédett [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Visszaadja a diagram adatpont színértékét. Térkép diagramoknál használatos. Írásvédett [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Visszaadja az adatpont szintek tárolóját. Fa és napkitörés sorozatoknál alkalmazott. Az adatpont szintek indexelése nulláról indul. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | A sorozat hibasáv értékeit jelöli egyéni értéktípus esetén. Írásvédett [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Meghatározza, hogy az adatpont mennyivel legyen eltolva a kördiagram középpontjától. Olvasás/írás Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | A formázási tulajdonságokat jelöli. Olvasás/írás [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Megadja, hogy az adatpont fordítsa meg színeit, ha az érték negatív. Olvasás/írás Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Megadja, hogy a buborékokra 3D hatás legyen alkalmazva. Olvasás/írás Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Írásvédett [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Megad egy adatjelölőt. Írásvédett [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | A megfelelő jelmagyarázat bejegyzés tulajdonságai a következő diagramtípusok esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Írásvédett [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Az adatpontot összegként állítja be. Csak Waterfall sorozattípusnál alkalmazható. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Visszaadja a diagram adatpont méretértékét. Treemap és Sunburst diagramoknál használatos. Írásvédett [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Írásvédett [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Írásvédett [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Írásvédett [`IDoubleChartValue`](../idoublechartvalue). |

## Módszerek

| Név | Leírás |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, a ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílusa alapján. Ez a szín alapértelmezés szerint használatos, ha a FillType NotDefined értékű. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Eltávolítja a DataPoint-ot a diagram sorozatából. |

### Lásd még

* interfész [IChartDataPoint](../ichartdatapoint)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->