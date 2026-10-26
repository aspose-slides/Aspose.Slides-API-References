---
title: IChartSeries
second_title: Aspose.Slides for Java API リファレンス
description: チャート系列を表します。
type: docs
url: /ja/com.aspose.slides/ichartseries/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

チャートシリーズを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getExplosion()](#getExplosion--) | 円グラフの開いたスライスの中心からの距離は、円の直径に対するパーセンテージで表されます。 |
| [setExplosion(int value)](#setExplosion-int-) | 円グラフの開いたスライスの中心からの距離は、円の直径に対するパーセンテージで表されます。 |
| [getSmooth()](#getSmooth--) | 曲線スムージングを表します。 |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 曲線スムージングを表します。 |
| [getMarker()](#getMarker--) | シリーズマーカーを返します。 |
| [getBar3DShape()](#getBar3DShape--) | 3-D バーチャートのシリーズの形状を指定します。 |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3-D バーチャートのシリーズの形状を指定します。 |
| [getName()](#getName--) | シリーズ名を返します。 |
| [getDataPoints()](#getDataPoints--) | このシリーズのデータポイントのコレクションを返します。 |
| [getType()](#getType--) | このシリーズのタイプを返します。 |
| [setType(int value)](#setType-int-) | このシリーズのタイプを返します。 |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | 親シリーズグループを返します。 |
| [getFormat()](#getFormat--) | シリーズのフォーマットを返します。 |
| [getOrder()](#getOrder--) | シリーズの順序を返します。 |
| [setOrder(int value)](#setOrder-int-) | シリーズの順序を返します。 |
| [getLabels()](#getLabels--) | シリーズのラベルを返します。 |
| [getTrendLines()](#getTrendLines--) | シリーズトレンドラインのコレクション 読み取り専用 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。 |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X 方向のシリーズのエラーバーを表します。 |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y 方向のシリーズのエラーバーを表します。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | このシリーズが第2軸にプロットされているかどうかを示します。 |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | このシリーズが第2軸にプロットされているかどうかを示します。 |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | シリーズの値の数値書式を取得または設定します。 |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | シリーズの値の数値書式を取得または設定します。 |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | シリーズの X 値の数値書式を取得または設定します。 |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | シリーズの X 値の数値書式を取得または設定します。 |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | シリーズの Y 値の数値書式を取得または設定します。 |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | シリーズの Y 値の数値書式を取得または設定します。 |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | シリーズのバブルサイズの数値書式を取得または設定します。 |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | シリーズのバブルサイズの数値書式を取得または設定します。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 値が負の場合、棒、列、またはバブルシリーズの色を反転させることを指定します。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 値が負の場合、棒、列、またはバブルシリーズの色を反転させることを指定します。 |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | シリーズの塗りつぶし色の反転を指定します。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | このシリーズに関連付けられた凡例エントリを表します（読み取り専用） [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | シリーズインデックスとチャートスタイルに基づく自動色を返します。 |
| [getShowInnerPoints()](#getShowInnerPoints--) | 内部ポイントを表します。 |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | 内部ポイントを表します。 |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | 外れ値ポイントを表します。 |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | 外れ値ポイントを表します。 |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | 平均マーカーを表します。 |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | 平均マーカーを表します。 |
| [getShowMeanLine()](#getShowMeanLine--) | 平均マーカーを表します。 |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | 平均マーカーを表します。 |
| [getQuartileMethod()](#getQuartileMethod--) | 四分位法を表します。 |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | 四分位法を表します。 |
| [getShowConnectorLines()](#getShowConnectorLines--) | コネクタラインを表します。 |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | コネクタラインを表します。 |
| [getParentLabelLayout()](#getParentLabelLayout--) | 親カテゴリラベルのレイアウトを表します。 |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 親カテゴリラベルのレイアウトを表します。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | バブルチャートのスケール係数を指定します（デフォルトサイズの0〜300％の範囲）。 |
| [hasUpDownBars()](#hasUpDownBars--) | 折れ線または株価チャートに上下バーがあるかどうかを決定します。 |
| [getGapWidth()](#getGapWidth--) | 棒または列クラスター間のスペースを、棒または列幅のパーセンテージで指定します。 |
| [getGapDepth()](#getGapDepth--) | 3Dチャートのデータシリーズ間の距離を、マーカー幅のパーセンテージで取得または設定します。 |
| [isColorVaried()](#isColorVaried--) | シリーズ内の各データマーカーに異なる色が付くことを指定します。 |
| [hasSeriesLines()](#hasSeriesLines--) | このシリーズおよび関連シリーズにシリーズラインがあるかどうかを決定します。 |
| [getOverlap()](#getOverlap--) | 2Dチャートで棒と列がどれだけ重なるかをパーセンテージで指定します（-100％から100％）。 |
| [getSecondPieSize()](#getSecondPieSize--) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2のパイまたはバーのサイズを、最初のパイのサイズのパーセンテージで指定します（5〜200％）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | パイ・オブ・パイまたはバー・オブ・パイチャートで第2のパイまたはバーに含めるデータポイントを決定するために使用される値を指定します。 |
| [getPieSplitBy()](#getPieSplitBy--) | パイ・オブ・パイまたはバー・オブ・パイチャートで第2のパイまたはバーに含めるデータポイントを決定する方法を指定します。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ドーナツチャートの穴のサイズを、プロット領域のサイズの10〜90％で指定します。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 最初のパイまたはドーナツチャートスライスの角度を度単位で指定します（上から時計回りに0〜360度）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | カスタム分割を使用したパイ・オブ・パイまたはバー・オブ・パイチャートのカスタム分割情報。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | バブルチャートでバブルサイズの値がどのように表されるかを指定します。 |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

円グラフの開いたスライスの中心からの距離は、円の直径に対するパーセンテージで表されます。読み取り/書き込み int。

**戻り値:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

円グラフの開いたスライスの中心からの距離は、円の直径に対するパーセンテージで表されます。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

曲線スムージングを表します。ラインチャートまたは散布図チャートで曲線スムージングがオンになっている場合に true です。ラインと散布図（ラインで接続）にのみ適用されます。読み取り/書き込み boolean。

**戻り値:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

曲線スムージングを表します。ラインチャートまたは散布図チャートで曲線スムージングがオンになっている場合に true です。ラインと散布図（ラインで接続）にのみ適用されます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

シリーズマーカーを返します。読み取り専用 [IMarker](../../com.aspose.slides/imarker)。

**戻り値:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

3-D バーチャートのシリーズの形状を指定します。値の変更によりシリーズの Type が自動的に変更される場合があります。読み取り/書き込み [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**戻り値:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

3-D バーチャートのシリーズの形状を指定します。値の変更によりシリーズの Type が自動的に変更される場合があります。読み取り/書き込み [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

シリーズ名を返します。読み取り専用 [IStringChartValue](../../com.aspose.slides/istringchartvalue)。

**戻り値:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

このシリーズのデータポイントのコレクションを返します。読み取り専用 [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)。

**戻り値:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

このシリーズのタイプを返します。読み取り/書き込み [ChartType](../../com.aspose.slides/charttype)。

**戻り値:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

このシリーズのタイプを返します。読み取り/書き込み [ChartType](../../com.aspose.slides/charttype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

親シリーズグループを返します。読み取り専用 [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)。

**戻り値:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

シリーズのフォーマットを返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

シリーズの順序を返します。読み取り/書き込み int。

**戻り値:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

シリーズの順序を返します。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

シリーズのラベルを返します。読み取り専用 [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)。

**戻り値:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

シリーズトレンドラインのコレクション 読み取り専用 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。

**戻り値:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

X 方向のシリーズのエラーバーを表します。読み取り専用 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

X 方向の ErrorBars は、area、bar、scatter、bubble タイプのシリーズで利用可能です。他のタイプのチャートではこのプロパティは null を返します（3D チャートを含む）。カスタム値を使用する場合は、DataPoints コレクションで値を指定してください（[IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) プロパティを使用）。

**戻り値:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Y 方向のシリーズのエラーバーを表します。読み取り専用 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

Y 方向の ErrorBars は、area、bar、line、scatter、bubble タイプのシリーズで利用可能です。他のタイプのチャートではこのプロパティは null を返します（3D チャートを含む）。カスタム値を使用する場合は、DataPoints コレクションで値を指定してください（[IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) プロパティを使用）。

**戻り値:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

このシリーズが第2軸にプロットされているかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

このシリーズが第2軸にプロットされているかどうかを示します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

シリーズの値の数値書式を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

シリーズの値の数値書式を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

シリーズの X 値の数値書式を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

シリーズの X 値の数値書式を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

シリーズの Y 値の数値書式を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

シリーズの Y 値の数値書式を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

シリーズのバブルサイズの数値書式を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

シリーズのバブルサイズの数値書式を取得または設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

棒、列、またはバブルシリーズの色を負の場合に反転させることを指定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

棒、列、またはバブルシリーズの色を負の場合に反転させることを指定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

シリーズの塗りつぶし色の反転を指定します。カラー設定を適用するには、シリーズのフォーマット FillType を FillType.Solid に設定してください。読み取り/書き込み [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

このシリーズに関連付けられた凡例エントリを表します（読み取り専用） [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined.

**戻り値:**
java.awt.Color - シリーズの自動カラー java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能な boolean。

**戻り値:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能な boolean。

**戻り値:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能な boolean。

**戻り値:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

平均マーカーを表します。BoxAndWhisker チャートで平均線が表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能な boolean。

**戻り値:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

平均マーカーを表します。BoxAndWhisker チャートで平均線が表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

四分位法を表します。BoxAndWhisker チャートにのみ適用されます。

**戻り値:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

四分位法を表します。BoxAndWhisker チャートにのみ適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

コネクタラインを表します。Waterfall チャートにのみ適用されます。

**戻り値:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

コネクタラインを表します。Waterfall チャートにのみ適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。

**戻り値:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

バブルチャートのスケール係数を指定します（既定サイズの 0% から 300% の間に設定できます）。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.BubbleSizeScale の読み書き可能なプロパティを使用します。

--------------------

これはプロパティ ParentSeriesGroup.BubbleSizeScale の投影です。

**戻り値:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Line または Stock チャートにアップ/ダウン バーがあるかを判定します。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars の読み書き可能なプロパティを使用します。アップ/ダウン バーの書式設定には ParentSeriesGroup.UpDownBars プロパティを使用します。読み取り専用の boolean。

--------------------

これはプロパティ ParentSeriesGroup.UpDownBars.HasUpDownBars の投影です。

**戻り値:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

バーまたは列のクラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.GapWidth の読み書き可能なプロパティを使用します。読み取り専用の int。

--------------------

これはプロパティ ParentSeriesGroup.GapWidth の投影です。

**戻り値:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.GapDepth の読み書き可能なプロパティを使用します。読み取り専用の int。

--------------------

これはプロパティ ParentSeriesGroup.GapDepth の投影です。

**戻り値:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

シリーズ内の各データマーカーが異なる色を持つことを指定します。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.IsColorVaried の読み書き可能なプロパティを使用します。読み取り専用の boolean。

--------------------

これはプロパティ ParentSeriesGroup.IsColorVaried の投影です。

**戻り値:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

このシリーズおよび関連シリーズにシリーズラインがあるかどうかを判定します。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.HasSeriesLines の読み書き可能なプロパティを使用します。シリーズラインの書式設定には ParentSeriesGroup.SeriesLinesFormat プロパティを使用します。読み取り専用の boolean。

--------------------

これはプロパティ ParentSeriesGroup.HasSeriesLines の投影です。

**戻り値:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2D チャートでバーと列がどれだけ重なるかを、パーセンテージ（-100% から 100%）で指定します。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されます。親シリーズグループの該当プロパティの投影であるため、読み取り専用です。値を変更するには ParentSeriesGroup.Overlap の読み書き可能なプロパティを使用します。読み取り専用の byte。

--------------------

Overlap は、バーと列の幅に対するパーセンテージで、重なりまたは間隔の度合いを指定します。- -100%: 最大の間隔（バーは完全に分離）。- 0%: バーは重なりや間隔なしで並びます。- 100%: 最大の重なり（バーは互いに完全に重なります）。これはプロパティ ParentSeriesGroup.Overlap の投影です。

**戻り値:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

パイ・オブ・パイ チャートまたはバー・オブ・パイ チャートの第二のパイまたはバーのサイズを、第一のパイのサイズのパーセンテージで指定します（5% から 200% の間に設定可能）。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.SecondPieSize の読み書き可能なプロパティを使用します。読み取り専用の int。

--------------------

これはプロパティ ParentSeriesGroup.SecondPieSize の投影です。

**戻り値:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

パイ・オブ・パイ または バー・オブ・パイ チャートで、どのデータポイントを第二のパイまたはバーに配置するかを決定するために使用される値を指定します。PieSplitBy プロパティと組み合わせて使用されます。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.PieSplitPosition の読み書き可能なプロパティを使用します。読み取り専用の double。

--------------------

これはプロパティ ParentSeriesGroup.PieSplitPosition の投影です。

**戻り値:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

どのデータポイントを第二のパイまたはバーに配置するかを決定する方法を指定します。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.PieSplitBy の読み書き可能なプロパティを使用します。読み取り専用 [PieSplitType](../../com.aspose.slides/piesplittype)。

--------------------

1) これはプロパティ ParentSeriesGroup.PieSplitBy の投影です。2) プロパティ値が PieSplitType.Custom の場合、ParentSeriesGroup.PieSplitCustomPoints プロパティでカスタム分割情報を定義できます。

**戻り値:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90% の間に設定可能）。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.DoughnutHoleSize の読み書き可能なプロパティを使用します。読み取り専用の byte。

--------------------

これはプロパティ ParentSeriesGroup.DoughnutHoleSize の投影です。

**戻り値:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

最初のパイまたはドーナツチャートのスライスの角度を度単位で指定します（上から時計回り、0 から 360 度）。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。そのため、読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。値を変更するには ParentSeriesGroup.FirstSliceAngle の読み書き可能なプロパティを使用します。読み取り専用の int。

--------------------

これはプロパティ ParentSeriesGroup.FirstSliceAngle の投影です。

**戻り値:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

カスタム分割が設定されたパイ・オブ・パイ または バー・オブ・パイ チャートのカスタム分割情報です。第二のパイまたはバーに描画されるデータポイントを含みます。このプロパティは、このシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されるプロパティの投影です。読み取り専用 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

--------------------

これはプロパティ ParentSeriesGroup.PieSplitCustomPoints の投影です。

**戻り値:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
バブル チャート上でバブル サイズの値がどのように表されるかを指定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されます - これは該当するグループ プロパティの投影です。このプロパティは読み取り専用です。親シリーズグループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.BubbleSizeRepresentation の読み書き可能プロパティを使用します。

--------------------

これはプロパティ ParentSeriesGroup.BubbleSizeRepresentation の投影です。

**戻り値:**
int