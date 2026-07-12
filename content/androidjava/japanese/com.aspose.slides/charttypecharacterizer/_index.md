---
title: ChartTypeCharacterizer
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ChartType に基づいてチャートと系列の追加情報を取得するヘルパーです。
type: docs
url: /ja/com.aspose.slides/charttypecharacterizer/
---
**継承:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

ChartType に基づいてチャートと系列の追加情報を取得するヘルパーです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | chartType が bar3DChart のサブタイプ（3D 列またはバー）のいずれかである場合に true を返します。 |
| [is2DChart(int chartType)](#is2DChart-int-) | chartType が 2D チャートタイプのいずれかである場合に true を返します。 |
| [is3DChart(int chartType)](#is3DChart-int-) | chartType が 3D チャートタイプのいずれかである場合に true を返します。 |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | chartType が Column のサブタイプのいずれかである場合に true を返します。 |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | chartType が Line のサブタイプのいずれかである場合に true を返します。 |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | chartType が Pie のサブタイプのいずれかである場合に true を返します。 |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | chartType が Bar のサブタイプのいずれかである場合に true を返します。 |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | chartType が Area のサブタイプのいずれかである場合に true を返します。 |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | chartType が Scatter のサブタイプのいずれかである場合に true を返します。 |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | chartType が Stock のサブタイプのいずれかである場合に true を返します。 |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | chartType が Surface のサブタイプのいずれかである場合に true を返します。 |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | chartType が Doughnut のサブタイプのいずれかである場合に true を返します。 |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | chartType が Bubble のサブタイプのいずれかである場合に true を返します。 |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | chartType が Radar のサブタイプのいずれかである場合に true を返します。 |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | 指定された series type が X 値座標を使用するかどうかを返します。 |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | 指定された series type が Y 値座標を使用するかどうかを返します。 |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | 指定された series type が値座標を使用するかどうかを返します。 |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | 指定された series type でバブルサイズ座標が使用できるかどうかを返します。 |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | 指定された series type に系列トレンドラインが存在するかどうかを返します。 |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | 指定された series type でエラーバー X が許可されているかどうかを返します。 |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | 指定された series type でエラーバー Y が許可されているかどうかを返します。 |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


chartType が bar3DChart のサブタイプ（3D 列またはバー）のいずれかである場合に true を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


chartType が 2D チャートタイプのいずれかである場合に true を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


chartType が 3D チャートタイプのいずれかである場合に true を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


chartType が Column のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


chartType が Line のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


chartType が Pie のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


chartType が Bar のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


chartType が Area のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


chartType が Scatter のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


chartType が Stock のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


chartType が Surface のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


chartType が Doughnut のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


chartType が Bubble のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


chartType が Radar のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の適切なセットに対応しています（PowerPoint の「Change Chart Type」ダイアログ参照）：[ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartType | int |  |

**戻り値:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


指定された series type が X 値座標を使用するかどうかを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**戻り値:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


指定された series type が Y 値座標を使用するかどうかを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**戻り値:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


指定された series type が値座標を使用するかどうかを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**戻り値:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


指定された series type でバブルサイズ座標が使用できるかどうかを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**戻り値:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


指定された series type に系列トレンドラインが存在するかどうかを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**戻り値:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


指定された series type でエラーバー X が許可されているかどうかを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**戻り値:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


指定された series type でエラーバー Y が許可されているかどうかを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| seriesType | int | Series type. |

**戻り値:**
boolean - True if allowed, otherwise false.