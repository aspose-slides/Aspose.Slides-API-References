---
title: ChartSeries
second_title: Aspose.Slides for Java API リファレンス
description: チャート系列を表します。
type: docs
url: /ja/com.aspose.slides/chartseries/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

チャート系列を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [getExplosion()](#getExplosion--) | 円グラフの中心から開いたパイスライスまでの距離は、円の直径のパーセンテージで示されます。 |
| [setExplosion(int value)](#setExplosion-int-) | 円グラフの中心から開いたパイスライスまでの距離は、円の直径のパーセンテージで示されます。 |
| [getSmooth()](#getSmooth--) | 曲線の平滑化を表します。 |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 曲線の平滑化を表します。 |
| [getName()](#getName--) | 系列名を返します。 |
| [getDataPoints()](#getDataPoints--) | この系列のデータポイントのコレクションを返します。 |
| [getType()](#getType--) | この系列のタイプを返します。 |
| [setType(int value)](#setType-int-) | この系列のタイプを返します。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | この系列が二次軸にプロットされているかどうかを示します。 |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | この系列が二次軸にプロットされているかどうかを示します。 |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup。 |
| [getFormat()](#getFormat--) | 系列のフォーマットを返します。 |
| [getOrder()](#getOrder--) | 系列の順序を返します。 |
| [setOrder(int value)](#setOrder-int-) | 系列の順序を返します。 |
| [getLabels()](#getLabels--) | 系列のラベルを返します。 |
| [getTrendLines()](#getTrendLines--) | 系列トレンドラインのコレクション。 |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X方向の系列エラーバーを表します。 |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y方向の系列エラーバーを表します。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | この系列に関連付けられた凡例エントリを表します（読み取り専用） [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | 3D 棒グラフの系列の形状を指定します。 |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3D 棒グラフの系列の形状を指定します。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 値が負の場合、棒、列、またはバブル系列の色を反転させることを指定します。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 値が負の場合、棒、列、またはバブル系列の色を反転させることを指定します。 |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | 系列の塗りつぶし色を反転させることを指定します。 |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | 系列インデックスとチャートスタイルに基づく自動カラーを返します。 |
| [getShowInnerPoints()](#getShowInnerPoints--) | 内部ポイントを表します。 |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | 内部ポイントを表します。 |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | 外れ値ポイントを表します。 |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | 外れ値ポイントを表します。 |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | 平均マーカーを表します。 |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | 平均マーカーを表します。 |
| [getShowMeanLine()](#getShowMeanLine--) | 平均線を表します。 |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | 平均線を表します。 |
| [getQuartileMethod()](#getQuartileMethod--) | 四分位法を表します。 |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | 四分位法を表します。 |
| [getShowConnectorLines()](#getShowConnectorLines--) | コネクタラインを表します。 |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | コネクタラインを表します。 |
| [getParentLabelLayout()](#getParentLabelLayout--) | 親カテゴリラベルのレイアウトを表します。 |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 親カテゴリラベルのレイアウトを表します。 |
| [hasUpDownBars()](#hasUpDownBars--) | ラインまたはストックチャートに上下バーがあるかどうかを決定します。 |
| [getGapWidth()](#getGapWidth--) | 棒または列クラスタ間のスペースを、棒または列の幅のパーセンテージで指定します。 |
| [getGapDepth()](#getGapDepth--) | マーカー幅のパーセンテージとして、3D チャート内のデータ系列間の距離を取得または設定します。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 最初のパイまたはドーナツチャートスライスの角度を度で指定します（上から時計回り、0〜360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ドーナツチャートの中心の穴のサイズを、描画領域のサイズの 10〜90 パーセントで指定します。 |
| [getOverlap()](#getOverlap--) | 2D チャートの棒と列の重なり具合をパーセンテージで指定します（-100%〜100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | パイ・オブ・パイやバー・オブ・パイチャートの第2のパイまたはバーのサイズを、第1のパイのサイズのパーセンテージで指定します（5〜200%）。 |
| [hasSeriesLines()](#hasSeriesLines--) | この系列と関連系列に系列線があるかどうかを決定します。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 第2のパイまたはバーに含まれるデータポイントを決定するために使用される値を指定します。 |
| [getPieSplitBy()](#getPieSplitBy--) | 第2のパイまたはバーに含まれるデータポイントを決定する方法を指定します。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | カスタム分割を持つ pie-of-pie または bar-of-pie チャートのカスタム分割情報です。 |
| [isColorVaried()](#isColorVaried--) | 系列内の各データマーカーが異なる色を持つことを指定します。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0〜300 パーセント）。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

親チャートを返します。読み取り専用 [IChart](../../com.aspose.slides/ichart)。

**戻り値:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

円グラフの中心から開いたパイスライスまでの距離は、円の直径のパーセンテージで示されます。読み書き可能な int。

**戻り値:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

円グラフの中心から開いたパイスライスまでの距離は、円の直径のパーセンテージで示されます。読み書き可能な int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

曲線の平滑化を表します。ラインチャートまたは散布図で平滑化がオンの場合は true です。ラインおよびラインで接続された散布図にのみ適用されます。読み書き可能な boolean。

**戻り値:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

曲線の平滑化を表します。ラインチャートまたは散布図で平滑化がオンの場合は true です。ラインおよびラインで接続された散布図にのみ適用されます。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

系列名を返します。読み取り専用 [IStringChartValue](../../com.aspose.slides/istringchartvalue)。

**戻り値:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

この系列のデータポイントのコレクションを返します。読み取り専用 [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)。

**戻り値:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

この系列のタイプを返します。読み書き可能 [ChartType](../../com.aspose.slides/charttype)。

**戻り値:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

この系列のタイプを返します。読み書き可能 [ChartType](../../com.aspose.slides/charttype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

この系列が二次軸にプロットされているかどうかを示します。読み書き可能な boolean。

**戻り値:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

この系列が二次軸にプロットされているかどうかを示します。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup。読み取り専用 [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)。

**戻り値:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

系列のフォーマットを返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

系列の順序を返します。読み書き可能な int。

**戻り値:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

系列の順序を返します。読み書き可能な int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

系列のラベルを返します。読み取り専用 [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)。

**戻り値:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

系列トレンドラインのコレクション。読み取り専用 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。

--------------------

TrendLines は、積み上げられていない 2D エリア、棒、列、ライン、ストック、XY（散布図）、バブルチャートのデータ系列で利用可能です（null ではありません）。スタック形式または 3D のチャートタイプのデータ系列では TrendLine は利用できません。また、レーダー、パイ、サーフェス、ドーナツチャートでも TrendLines は利用できません。

**戻り値:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

方向 X の系列エラーバーを表します。読み取り専用 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

X 方向の ErrorBars は、エリア、棒、散布図、バブルのタイプの系列で利用可能です。他のチャートタイプではこのプロパティは null を返します（3D チャートを含む）。カスタム値の場合は、DataPoints コレクションを使用して値を指定します（[IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) プロパティを使用）。

**戻り値:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

方向 Y の系列エラーバーを表します。読み取り専用 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

Y 方向の ErrorBars は、エリア、棒、ライン、散布図、バブルのタイプの系列で利用可能です。他のチャートタイプではこのプロパティは null を返します（3D チャートを含む）。カスタム値の場合は、DataPoints コレクションを使用して値を指定します（[IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) プロパティを使用）。

**戻り値:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

この系列に関連付けられた凡例エントリを表します（読み取り専用） [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues。読み書き可能な String。

**戻り値:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues。読み書き可能な String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues。読み書き可能な String。

**戻り値:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues。読み書き可能な String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues。読み書き可能な String。

**戻り値:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues。読み書き可能な String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes。読み書き可能な String。

**戻り値:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes。読み書き可能な String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker。読み取り専用 [IMarker](../../com.aspose.slides/imarker)。

**戻り値:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

3D 棒グラフの系列の形状を指定します。このプロパティの値を変更すると、系列のタイプが自動的に変更される可能性があります。読み書き可能 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**戻り値:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

3D 棒グラフの系列の形状を指定します。このプロパティの値を変更すると、系列のタイプが自動的に変更される可能性があります。読み書き可能 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

値が負の場合、棒、列、またはバブル系列の色を反転させることを指定します。読み書き可能な boolean。

**戻り値:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

値が負の場合、棒、列、またはバブル系列の色を反転させることを指定します。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
シリーズの反転ソリッドカラーを指定します。カラー設定を適用するには、シリーズの形式 FillType を FillType.Solid に設定します。読み書き [ColorFormat](../../com.aspose.slides/colorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

シリーズのインデックスとチャートスタイルに基づく自動カラーを返します。FillType が NotDefined の場合、このカラーがデフォルトで使用されます。

**戻り値:**
java.awt.Color - java.awt.Color オブジェクト。
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き boolean。

**戻り値:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き boolean。

**戻り値:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き boolean。

**戻り値:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

平均線を表します。BoxAndWhisker チャートで平均線が表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き boolean。

**戻り値:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

平均線を表します。BoxAndWhisker チャートで平均線が表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

四分位法を表します。BoxAndWhisker チャートにのみ適用されます。

**戻り値:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

四分位法を表します。BoxAndWhisker チャートにのみ適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

コネクタラインを表します。Waterfall チャートにのみ適用されます。

**戻り値:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

コネクタラインを表します。Waterfall チャートにのみ適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。

**戻り値:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Line または Stock チャートに上下バーがあるかどうかを判定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars の読み書きプロパティを使用します。上下バーの書式設定には ParentSeriesGroup.UpDownBars プロパティを使用します。読み取り専用 boolean。

--------------------

これはプロパティ ParentSeriesGroup.UpDownBars.HasUpDownBars の投影です。

**戻り値:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

バーまたは列クラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.GapWidth の読み書きプロパティを使用します。読み取り専用 int。

--------------------

これはプロパティ ParentSeriesGroup.GapWidth の投影です。

**戻り値:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D チャートでデータシリーズ間の距離を、マーカー幅のパーセンテージで取得または設定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.GapDepth の読み書きプロパティを使用します。読み取り専用 int。

--------------------

これはプロパティ ParentSeriesGroup.GapDepth の投影です。

**戻り値:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

円またはドーナツチャートの最初のスライスの角度を、度数（上から時計回り、0〜360 度）で指定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.FirstSliceAngle の読み書きプロパティを使用します。読み取り専用 int。

--------------------

これはプロパティ ParentSeriesGroup.FirstSliceAngle の投影です。

**戻り値:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

ドーナツチャートの穴のサイズを、プロット領域のサイズに対するパーセンテージ（10〜90%）で指定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.DoughnutHoleSize の読み書きプロパティを使用します。読み取り専用 byte。

--------------------

これはプロパティ ParentSeriesGroup.DoughnutHoleSize の投影です。

**戻り値:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2-D チャートでバーと列がどれだけ重なるかを、パーセンテージ（-100%〜100%）で指定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影です。そのためこのプロパティは読み取り専用です。値を変更するには ParentSeriesGroup.Overlap の読み書きプロパティを使用します。読み取り専用 byte。

--------------------

Overlap はバーと列の幅に対する重なりまたは間隔の度合いをパーセンテージで指定します:
- -100%: 最大間隔（バーは完全に分離）
- 0%: 重なりも間隔もなく隣り合って配置
- 100%: 最大重なり（バーは完全に重なる）

これはプロパティ ParentSeriesGroup.Overlap の投影です。

**戻り値:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

円内円または棒内棒チャートの第2の円または棒のサイズを、最初の円のサイズに対するパーセンテージ（5〜200%）で指定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.SecondPieSize の読み書きプロパティを使用します。読み取り専用 int。

--------------------

これはプロパティ ParentSeriesGroup.SecondPieSize の投影です。

**戻り値:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

このシリーズおよび関連シリーズにシリーズラインがあるかどうかを判定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.HasSeriesLines の読み書きプロパティを使用します。シリーズラインの書式設定には ParentSeriesGroup.SeriesLinesFormat プロパティを使用します。読み取り専用 boolean。

--------------------

これはプロパティ ParentSeriesGroup.HasSeriesLines の投影です。

**戻り値:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

バブルチャートでバブルサイズの値がどのように表現されるかを指定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.BubbleSizeRepresentation の読み書きプロパティを使用します。

--------------------

これはプロパティ ParentSeriesGroup.BubbleSizeRepresentation の投影です。

**戻り値:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

円内円または棒内棒チャートで第2の円または棒に含めるデータポイントを決定するために使用される値を指定します。PieSplitBy プロパティと組み合わせて使用します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.PieSplitPosition の読み書きプロパティを使用します。読み取り専用 double。

--------------------

これはプロパティ ParentSeriesGroup.PieSplitPosition の投影です。

**戻り値:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

円内円または棒内棒チャートで第2の円または棒に含めるデータポイントを決定する方法を指定します。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。そのためこのプロパティは読み取り専用です。親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.PieSplitBy の読み書きプロパティを使用します。読み取り専用 [PieSplitType](../../com.aspose.slides/piesplittype)。

--------------------

1) これはプロパティ ParentSeriesGroup.PieSplitBy の投影です。2) プロパティ値が PieSplitType.Custom の場合、ParentSeriesGroup.PieSplitCustomPoints プロパティでカスタム分割情報を定義できます。

**戻り値:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

カスタム分割情報は、円内円または棒内棒チャートでカスタム分割を使用する際に、第2の円または棒に描画されるデータポイントを含みます。これはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対するプロパティの投影です。読み取り専用 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

--------------------

これはプロパティ ParentSeriesGroup.PieSplitCustomPoints の投影です。

**戻り値:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**Returns:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```


Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**Returns:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)