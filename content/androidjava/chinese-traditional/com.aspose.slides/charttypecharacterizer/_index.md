---
title: ChartTypeCharacterizer
second_title: Aspose.Slides for Android via Java API 參考
description: 用於根據其 ChartType 取得圖表和系列的其他資訊的輔助工具。
type: docs
url: /zh-hant/com.aspose.slides/charttypecharacterizer/
---
**繼承:**  
java.lang.Object
```
public class ChartTypeCharacterizer
```

用於取得有關圖表與系列之 ChartType 的其他資訊之輔助工具。
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | 如果 chartType 為 bar3DChart 子類型之一（3D 欄或條），則回傳 true。 |
| [is2DChart(int chartType)](#is2DChart-int-) | 如果 chartType 為 2D 圖表類型之一，則回傳 true。 |
| [is3DChart(int chartType)](#is3DChart-int-) | 如果 chartType 為 3D 圖表類型之一，則回傳 true。 |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | 如果 chartType 為 Column 子類型之一，則回傳 true。 |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | 如果 chartType 為 Line 子類型之一，則回傳 true。 |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | 如果 chartType 為 Pie 子類型之一，則回傳 true。 |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | 如果 chartType 為 Bar 子類型之一，則回傳 true。 |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | 如果 chartType 為 Area 子類型之一，則回傳 true。 |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | 如果 chartType 為 Scatter 子類型之一，則回傳 true。 |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | 如果 chartType 為 Stock 子類型之一，則回傳 true。 |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | 如果 chartType 為 Surface 子類型之一，則回傳 true。 |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | 如果 chartType 為 Doughnut 子類型之一，則回傳 true。 |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | 如果 chartType 為 Bubble 子類型之一，則回傳 true。 |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | 如果 chartType 為 Radar 子類型之一，則回傳 true。 |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | 如果指定的 series type 使用 X 值座標，則回傳。 |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | 如果指定的 series type 使用 Y 值座標，則回傳。 |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | 如果指定的 series type 使用數值座標，則回傳。 |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | 如果指定的 series type 可使用氣泡大小座標，則回傳。 |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | 如果指定的 series type 有趨勢線，則回傳。 |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | 如果指定的 series type 允許 X 誤差棒，則回傳。 |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | 如果指定的 series type 允許 Y 誤差棒，則回傳。 |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


如果 chartType 為 bar3DChart 子類型之一（3D 欄或條），則回傳 true。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


如果 chartType 為 2D 圖表類型之一，則回傳 true。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


如果 chartType 為 3D 圖表類型之一，則回傳 true。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


如果 chartType 為 Column 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


如果 chartType 為 Line 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


如果 chartType 為 Pie 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


如果 chartType 為 Bar 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


如果 chartType 為 Area 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


如果 chartType 為 Scatter 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


如果 chartType 為 Stock 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


如果 chartType 為 Surface 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


如果 chartType 為 Doughnut 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


如果 chartType 為 Bubble 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


如果 chartType 為 Radar 子類型之一，則回傳 true。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartType | int |  |

**回傳:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


如果指定的 series type 使用 X 值座標，則回傳。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**回傳:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


如果指定的 series type 使用 Y 值座標，則回傳。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**回傳:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


如果指定的 series type 使用數值座標，則回傳。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**回傳:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


如果指定的 series type 可使用氣泡大小座標，則回傳。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**回傳:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


如果指定的 series type 有趨勢線，則回傳。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**回傳:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


如果指定的 series type 允許 X 誤差棒，則回傳。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**回傳:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


如果指定的 series type 允許 Y 誤差棒，則回傳。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**回傳:**
boolean - True if allowed, otherwise false.