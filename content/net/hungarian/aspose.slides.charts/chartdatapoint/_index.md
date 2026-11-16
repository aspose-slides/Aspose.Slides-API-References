---
title: ChartDataPoint
second_title: Aspose.Sildes .NET API referencia
description: A sorozat adatpontját képviseli.
type: docs
weight: 1340
url: /hu/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint osztály

A sorozat adatpontját képviseli.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Tulajdonságok

| Name | Description |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Megadja a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Megadja a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Megadja a diagram elem tényleges x helyzetét (bal), a diagram bal felső sarkához viszonyítva. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Megadja a diagram elem tényleges felső pozícióját a diagram bal felső sarkához viszonyítva. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Olvasás Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Lekéri a diagram adatpontjának gyorsítótárazott buborékméretét. Csak olvasható [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Lekéri a diagram adatpontjának gyorsítótárazott értékét. Csak olvasható [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Lekéri a diagram adatpontjának gyorsítótárazott X értékét. Csak olvasható [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Lekéri a diagram adatpontjának gyorsítótárazott Y értékét. Csak olvasható [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Visszaadja a diagram adatpont színértékét. Térképes diagramoknál használatos. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Visszaadja az adatpont szintek tárolóját. Fa- és Sunburst-sorozatoknál alkalmazható. Az adatpont szintjei nulla-alapúak. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Megadja a sorozat hibasáv értékeit egyéni értéktípus esetén. Csak olvasható [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Meghatározza, hogy az adatpont mennyivel legyen eltolva a kör diagram középpontjától. Olvasás/írás Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | A formázási tulajdonságokat képviseli. Olvasás/írás [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Meghatározza, hogy az adatpont színe invertálódjon-e, ha az érték negatív. Olvasás/írás Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Meghatározza, hogy a buborékokra 3-D hatás legyen alkalmazva. Olvasás/írás Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Címke. Csak olvasható [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Megad egy adatjelölőt. Csak olvasható [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | A megfelelő jelmagyarázat bejegyzésének tulajdonságai a következő diagramtípusok esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Csak olvasható [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Beállítja az adatpontot összegként. Csak a Waterfall sorozattípusnál alkalmazható. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Visszaadja a diagram adatpont méretértékét. Treemap és Sunburst diagramoknál használatos. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Érték. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Csak olvasható [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |

## Módszerek

| Name | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Visszaad egy automatikus színt az adatpontra a sorozat indexe, adatpont indexe, a ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílus alapján. Ez a szín az alapértelmezett, ha a FillType értéke NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Eltávolítja az adatpontot a diagram sorozatból. |

### Lásd még

* interfész [IChartDataPoint](../ichartdatapoint)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->