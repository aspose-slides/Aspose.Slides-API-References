---
title: ChartSeries
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: チャート系列を表します。
type: docs
url: /ja/com.aspose.slides/chartseries/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
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
| [getExplosion()](#getExplosion--) | 開いたパイスライスの中心からの距離は、パイの直径のパーセンテージで表されます。 |
| [setExplosion(int value)](#setExplosion-int-) | 開いたパイスライスの中心からの距離は、パイの直径のパーセンテージで表されます。 |
| [getSmooth()](#getSmooth--) | 曲線のスムージングを表します。 |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 曲線のスムージングを表します。 |
| [getName()](#getName--) | 系列名を返します。 |
| [getDataPoints()](#getDataPoints--) | この系列のデータポイントのコレクションを返します。 |
| [getType()](#getType--) | この系列のタイプを返します。 |
| [setType(int value)](#setType-int-) | この系列のタイプを返します。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | この系列が副軸にプロットされているかどうかを示します。 |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | この系列が副軸にプロットされているかどうかを示します。 |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup。 |
| [getFormat()](#getFormat--) | 系列の書式を返します。 |
| [getOrder()](#getOrder--) | 系列の順序を返します。 |
| [setOrder(int value)](#setOrder-int-) | 系列の順序を返します。 |
| [getLabels()](#getLabels--) | 系列のラベルを返します。 |
| [getTrendLines()](#getTrendLines--) | 系列トレンドラインのコレクション。 |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X 方向のエラーバーを表します。 |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y 方向のエラーバーを表します。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | この系列に関連する凡例エントリを表します（読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)）。 |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues。 |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues。 |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues。 |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues。 |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues。 |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues。 |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes。 |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes。 |
| [getMarker()](#getMarker--) | Marker。 |
| [getBar3DShape()](#getBar3DShape--) | 3-D 棒グラフの系列の形状を指定します。 |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3-D 棒グラフの系列の形状を指定します。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 値が負の場合、棒、柱、バブル系列の色を反転させます。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 値が負の場合、棒、柱、バブル系列の色を反転させます。 |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | 系列の塗りつぶし色を反転させます。 |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | 系列インデックスとチャートスタイルに基づく自動色を返します。 |
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
| [getShowConnectorLines()](#getShowConnectorLines--) | コネクタ線を表します。 |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | コネクタ線を表します。 |
| [getParentLabelLayout()](#getParentLabelLayout--) | 親カテゴリラベルのレイアウトを表します。 |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 親カテゴリラベルのレイアウトを表します。 |
| [hasUpDownBars()](#hasUpDownBars--) | 折れ線または株価チャートに上下バーがあるかどうかを決定します。 |
| [getGapWidth()](#getGapWidth--) | 棒または柱のクラスター間のスペースを、棒または柱の幅のパーセンテージで指定します。 |
| [getGapDepth()](#getGapDepth--) | 3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 最初のパイまたはドーナツスライスの角度を度単位で指定します（上から時計回り、0〜360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ドーナツチャートの穴のサイズを指定します（プロット領域サイズの 10%〜90% の範囲）。 |
| [getOverlap()](#getOverlap--) | 2-D チャートで棒と柱がどれだけ重なるかをパーセンテージで指定します（-100%〜100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | ピー・オブ・ピーまたはバー・オブ・ピー チャートで、第二のパイまたはバーのサイズを第一のパイのサイズのパーセンテージで指定します（5%〜200% の範囲）。 |
| [hasSeriesLines()](#hasSeriesLines--) | この系列および関連系列に系列線があるかどうかを決定します。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | バブルチャートでバブルサイズ値がどのように表現されるかを指定します。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | ピー・オブ・ピーまたはバー・オブ・ピー チャートで第二のパイまたはバーに含めるデータポイントを決定する値を指定します。 |
| [getPieSplitBy()](#getPieSplitBy--) | ピー・オブ・ピーまたはバー・オブ・ピー チャートで第二のパイまたはバーに含めるデータポイントを決定する方法を指定します。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | カスタム分割情報を保持するピ―・オブ・ピーまたはバー・オブ・ピー チャート用のカスタム分割です。 |
| [isColorVaried()](#isColorVaried--) | 系列内の各データマーカーに異なる色を使用するかどうかを指定します。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0%〜300% の範囲）。 |
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

開いたパイスライスの中心からの距離は、パイの直径のパーセンテージで表されます。読み取り/書き込み int。

**戻り値:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

開いたパイスライスの中心からの距離は、パイの直径のパーセンテージで表されます。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

曲線のスムージングを表します。ラインチャートまたは散布図チャートで曲線スムージングが有効な場合は true です。ラインおよびラインで接続された散布図チャートにのみ適用されます。読み取り/書き込み boolean。

**戻り値:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

曲線のスムージングを表します。ラインチャートまたは散布図チャートで曲線スムージングが有効な場合は true です。ラインおよびラインで接続された散布図チャートにのみ適用されます。読み取り/書き込み boolean。

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

この系列のタイプを返します。読み取り/書き込み [ChartType](../../com.aspose.slides/charttype)。

**戻り値:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

この系列のタイプを返します。読み取り/書き込み [ChartType](../../com.aspose.slides/charttype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

この系列が副軸にプロットされているかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

この系列が副軸にプロットされているかどうかを示します。読み取り/書き込み boolean。

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

系列の書式を返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

系列の順序を返します。読み取り/書き込み int。

**戻り値:**
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

系列の順序を返します。読み取り/書き込み int。

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

TrendLines は、スタックされていない 2-D エリア、棒、柱、ライン、株価、散布 (XY)、バブル チャートのデータ系列で利用可能です（null ではありません）。スタックされたチャートや 3-D チャートでは利用できません。また、レーダー、パイ、サーフェス、ドーナツチャートでも利用できません。

**戻り値:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

X 方向のエラーバーを表します。読み取り専用 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

X 方向のエラーバーは、エリア、棒、散布、バブル系統で利用できます。その他のチャートタイプ（3D を含む）ではこのプロパティは null を返します。カスタム値を使用する場合は DataPoints コレクションで値を指定します（[IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) プロパティを使用）。

**戻り値:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Y 方向のエラーバーを表します。読み取り専用 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

Y 方向のエラーバーは、エリア、棒、ライン、散布、バブル系統で利用できます。その他のチャートタイプ（3D を含む）ではこのプロパティは null を返します。カスタム値を使用する場合は DataPoints コレクションで値を指定します（[IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) プロパティを使用）。

**戻り値:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

この系列に関連する凡例エントリを表します（読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)）。

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes。読み取り/書き込み String。

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

3-D 棒チャートの系列の形状を指定します。このプロパティの値を変更すると、系列の Type が自動的に変更される可能性があります。読み取り/書き込み [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**戻り値:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

3-D 棒チャートの系列の形状を指定します。このプロパティの値を変更すると、系列の Type が自動的に変更される可能性があります。読み取り/書き込み [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

値が負の場合、棒、柱、バブル系列の色を反転させます。読み取り/書き込み boolean。

**戻り値:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

値が負の場合、棒、柱、バブル系列の色を反転させます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

系列の塗りつぶし色を反転させます。色設定を適用するには、系列書式の FillType を FillType.Solid に設定してください。読み取り/書き込み [ColorFormat](../../com.aspose.slides/colorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

系列インデックスとチャートスタイルに基づく自動色を返します。この色は FillType が NotDefined の場合にデフォルトで使用されます。

**戻り値:**
java.lang.Integer - The java.lang.Integer object.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り/書き込み boolean。

**戻り値:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り/書き込み boolean。

**戻り値:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り/書き込み boolean。

**戻り値:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

平均線を表します。BoxAndWhisker チャートで平均線が表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り/書き込み boolean。

**戻り値:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

平均線を表します。BoxAndWhisker チャートで平均線が表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

コネクタ線を表します。Waterfall チャートにのみ適用されます。

**戻り値:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

コネクタ線を表します。Waterfall チャートにのみ適用されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

折れ線または株価チャートに上下バーがあるかどうかを決定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用される投影です。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars の読み取り/書き込みプロパティを使用します。上下バーの書式設定には ParentSeriesGroup.UpDownBars プロパティを使用します。読み取り専用 boolean。

--------------------

これはプロパティ ParentSeriesGroup.UpDownBars.HasUpDownBars の投影です。

**戻り値:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

棒または柱のクラスター間のスペースを、棒または柱の幅のパーセンテージで指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用される投影です。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.GapWidth の読み取り/書き込みプロパティを使用します。読み取り専用 int。

--------------------

これはプロパティ ParentSeriesGroup.GapWidth の投影です。

**戻り値:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D チャートでデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用される投影です。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.GapDepth の読み取り/書き込みプロパティを使用します。読み取り専用 int。

--------------------

これはプロパティ ParentSeriesGroup.GapDepth の投影です。

**戻り値:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

最初のパイまたはドーナツスライスの角度を度単位で指定します（上から時計回り、0〜360 度）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用される投影です。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.FirstSliceAngle の読み取り/書き込みプロパティを使用します。読み取り専用 int。

--------------------

これはプロパティ ParentSeriesGroup.FirstSliceAngle の投影です。

**戻り値:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

ドーナツチャートの穴のサイズを指定します（プロット領域サイズの 10%〜90% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用される投影です。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.DoughnutHoleSize の読み取り/書き込みプロパティを使用します。読み取り専用 byte。

--------------------

これはプロパティ ParentSeriesGroup.DoughnutHoleSize の投影です。

**戻り値:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2-D チャートで棒と柱がどれだけ重なるかをパーセンテージで指定します（-100%〜100%）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に投影されます。したがって読み取り専用です。値を変更するには ParentSeriesGroup.Overlap の読み取り/書き込みプロパティを使用してください。読み取り専用 byte。

--------------------

Overlap は棒と柱の幅に対する重なりまたは間隔の度合いをパーセンテージで示します:
- -100%: 最大間隔（棒は完全に分離）。
- 0%: 棒は重なりも間隔もなく並んで配置。
- 100%: 最大重なり（棒は完全に重なる）。
これはプロパティ ParentSeriesGroup.Overlap の投影です。

**戻り値:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

ピー・オブ・ピーまたはバー・オブ・ピー チャートで、第二のパイまたはバーのサイズを第一のパイのサイズのパーセンテージで指定します（5%〜200% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に投影されます。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.SecondPieSize の読み取り/書き込みプロパティを使用します。読み取り専用 int。

--------------------

これはプロパティ ParentSeriesGroup.SecondPieSize の投影です。

**戻り値:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

この系列と関連系列に系列線があるかどうかを決定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に投影されます。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.HasSeriesLines の読み取り/書き込みプロパティを使用します。系列線の書式設定には ParentSeriesGroup.SeriesLinesFormat プロパティを使用してください。読み取り専用 boolean。

--------------------

これはプロパティ ParentSeriesGroup.HasSeriesLines の投影です。

**戻り値:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

バブルチャートでバブルサイズ値がどのように表現されるかを指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に投影されます。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.BubbleSizeRepresentation の読み取り/書き込みプロパティを使用します。

--------------------

これはプロパティ ParentSeriesGroup.BubbleSizeRepresentation の投影です。

**戻り値:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

ピー・オブ・ピーまたはバー・オブ・ピー チャートで第二のパイまたはバーに含めるデータポイントを決定するために使用される値を指定します。PieSplitBy プロパティと共に使用されます。このプロパティはこの系列だけでなく、親系列グループのすべての系列に投影されます。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.PieSplitPosition の読み取り/書き込みプロパティを使用します。読み取り専用 double。

--------------------

これはプロパティ ParentSeriesGroup.PieSplitPosition の投影です。

**戻り値:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

ピー・オブ・ピーまたはバー・オブ・ピー チャートで第二のパイまたはバーに含めるデータポイントを決定する方法を指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に投影されます。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.PieSplitBy の読み取り/書き込みプロパティを使用します。読み取り専用 [PieSplitType](../../com.aspose.slides/piesplittype)。

--------------------

1) これはプロパティ ParentSeriesGroup.PieSplitBy の投影です。2) プロパティ値が PieSplitType.Custom の場合、ParentSeriesGroup.PieSplitCustomPoints プロパティでカスタム分割情報を定義できます。

**戻り値:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

カスタム分割情報は、カスタム分割を持つピー・オブ・ピーまたはバー・オブ・ピー チャート用です。第二のパイまたはバーに描画されるデータポイントを含みます。このプロパティはこの系列だけでなく、親系列グループのすべての系列に投影されます。読み取り専用 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

--------------------

これはプロパティ ParentSeriesGroup.PieSplitCustomPoints の投影です。

**戻り値:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

系列内の各データマーカーが異なる色を持つかどうかを指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に投影されます。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.IsColorVaried の読み取り/書き込みプロパティを使用します。読み取り専用 boolean。

--------------------

これはプロパティ ParentSeriesGroup.IsColorVaried の投影です。

**戻り値:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

バブルチャートのスケール係数を指定します（デフォルトサイズの 0%〜300% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に投影されます。そのため読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.BubbleSizeScale の読み取り/書き込みプロパティを使用します。

--------------------

これはプロパティ ParentSeriesGroup.BubbleSizeScale の投影です。

**戻り値:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat の親スライドを返します。読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat の親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)