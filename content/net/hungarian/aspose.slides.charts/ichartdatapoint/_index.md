---
title: IChartDataPoint
second_title: Aspose.Sildes .NET API referencia
description: Sorozat adatpontot képvisel.
type: docs
weight: 1840
url: /hu/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint interfész

Sorozat adatpontot képvisel.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Visszaadja az IActualLayout interfészt. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | A diagram adatpont buborékméretét adja vissza. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Az adatpont gyorsítótárazott buborékméretét adja vissza. Csak olvasható [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Az adatpont gyorsítótárazott értékét adja vissza. Csak olvasható [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Az adatpont gyorsítótárazott X értékét adja vissza. Csak olvasható [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Az adatpont gyorsítótárazott Y értékét adja vissza. Csak olvasható [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Az adatpont színértékét adja vissza. Map diagramoknál használt. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Visszaadja az adatpont szintek tárolóját. Treeamp és Sunburst sorozatoknál alkalmazott. Az adatpont szintek indexelése nullától indul. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | A sorozat hibasáv értékeket reprezentálja egyéni értéktípus esetén. Csak olvasható [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Meghatározza, hogy az adatpont mennyivel legyen eltolva a kördiagram középpontjától. Olvas/írás Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | A formázási tulajdonságokat reprezentálja. Olvas/írás [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Meghatározza, hogy a szülő gyermekgyűjteményének melyik eleme ez az adatpont. Olvas UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Megadja, hogy az adatpont negatív érték esetén invertálja a színeket. Olvas/írás Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Megadja, hogy a buborékokra 3-D hatás legyen alkalmazva. Olvas/írás Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | A diagram adatpont címkéjét reprezentálja. Csak olvasható [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Adatjelzőt ad meg. Csak olvasható [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Az adott diagramtípushoz (ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie) tartozó jelmagyarázat-bejegyzés tulajdonságai. Csak olvasható [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Az adatpontot összegként állítja be. Csak a Waterfall sorozattípusnál alkalmazott. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | A diagram adatpont méretértékét adja vissza. Treemap és Sunburst diagramoknál használt. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | A diagram adatpont értékét adja vissza. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | A diagram adatpont x értékét adja vissza. Csak olvasható [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | A diagram adatpont y értékét adja vissza. Csak olvasható [`IDoubleChartValue`](../idoublechartvalue). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, a ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílusa alapján. Ez a szín alapértelmezésként használatos, ha a FillType értéke NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Eltávolítja a DataPoint-ot a diagram sorozatból. |

### Lásd még

* interfész [IActualLayout](../iactuallayout)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->