---
title: ChartDataPoint
second_title: Aspose.Slides for Android の Java API リファレンス
description: シリーズ データポイントを表します。
type: docs
url: /ja/com.aspose.slides/chartdatapoint/
---
**継承:**
java.lang.Object

**すべての実装インターフェイス:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

シリーズデータポイントを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | チャート データ ポイントのサイズ値を返します。 |
| [getColorValue()](#getColorValue--) | チャート データ ポイントのカラー値を返します。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | カスタム 値タイプの場合のシリーズ誤差バーの値を表します。 |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | バブルに 3D 効果が適用されていることを指定します。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | バブルに 3D 効果が適用されていることを指定します。 |
| [getExplosion()](#getExplosion--) | データ ポイントが円グラフの中心から移動する量を指定します。 |
| [setExplosion(int value)](#setExplosion-int-) | データ ポイントが円グラフの中心から移動する量を指定します。 |
| [getFormat()](#getFormat--) | 書式設定プロパティを表します。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 書式設定プロパティを表します。 |
| [getMarker()](#getMarker--) | データ マーカーを指定します。 |
| [getSetAsTotal()](#getSetAsTotal--) | データ ポイントを合計として設定します。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | データ ポイントを合計として設定します。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie のいずれかのチャートタイプの場合の対応する凡例エントリのプロパティ。 |
| [remove()](#remove--) | チャート シリーズから DataPoint を削除します。 |
| [getDataPointLevels()](#getDataPointLevels--) | データ ポイント レベルのコンテナを返します。 |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | シリーズインデックス、データ ポイント インデックス、ParentSeriesGroup.IsColorVaried プロパティ、およびチャート スタイルに基づくデータ ポイントの自動カラーを返します。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 値が負の場合、データ ポイントの色を反転させることを指定します。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 値が負の場合、データ ポイントの色を反転させることを指定します。 |
| [getActualX()](#getActualX--) | チャート要素の実際の X 座標（左）を、チャートの左上隅に対して指定します。 |
| [getActualY()](#getActualY--) | チャート要素の実際の上位置を、チャートの左上隅に対して指定します。 |
| [getActualWidth()](#getActualWidth--) | チャート要素の実際の幅を指定します。 |
| [getActualHeight()](#getActualHeight--) | チャート要素の実際の高さを指定します。 |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue。 読み取り専用 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)。

**戻り値:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue。 読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize。 読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value。 読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

チャート データ ポイントのサイズ値を返します。 Treemap および Sunburst チャートで使用されます。 読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

チャート データ ポイントのカラー値を返します。 Map チャートで使用されます。 読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

カスタム 値タイプの場合のシリーズ誤差バーの値を表します。 読み取り専用 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**戻り値:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label。 読み取り専用 [IDataLabel](../../com.aspose.slides/idatalabel)。

**戻り値:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

バブルに 3D 効果が適用されていることを指定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

バブルに 3D 効果が適用されていることを指定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

データ ポイントが円グラフの中心から移動する量を指定します。 読み取り/書き込み int。

**戻り値:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

データ ポイントが円グラフの中心から移動する量を指定します。 読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

書式設定プロパティを表します。 読み取り/書き込み [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

書式設定プロパティを表します。 読み取り/書き込み [IFormat](../../com.aspose.slides/iformat)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

データ マーカーを指定します。 読み取り専用 [IMarker](../../com.aspose.slides/imarker)。

**戻り値:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

データ ポイントを合計として設定します。 Waterfall 系列タイプにのみ適用されます。

**戻り値:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

データ ポイントを合計として設定します。 Waterfall 系列タイプにのみ適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie のいずれかのチャートタイプの場合の対応する凡例エントリのプロパティ。 読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

チャート シリーズから DataPoint を削除します。

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

データ ポイント レベルのコンテナを返します。 Treeamp および Sunburst 系列に適用されます。 データ ポイント レベルのインデックスは 0 ベースです。

**戻り値:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```

  

**戻り値:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。 読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

シリーズインデックス、データ ポイント インデックス、ParentSeriesGroup.IsColorVaried プロパティ、およびチャート スタイルに基づくデータ ポイントの自動カラーを返します。 FillType が NotDefined の場合はこのカラーがデフォルトで使用されます。

**戻り値:**
java.lang.Integer
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

値が負の場合、データ ポイントの色を反転させることを指定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

値が負の場合、データ ポイントの色を反転させることを指定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

チャート要素の実際の X 座標（左）を、チャートの左上隅に対して指定します。実際の値を取得するには IChart.ValidateChartLayout() を事前に呼び出してください。 読み取り float。

**戻り値:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

チャート要素の実際の上位置を、チャートの左上隅に対して指定します。実際の値を取得するには IChart.ValidateChartLayout() を事前に呼び出してください。 読み取り float。

**戻り値:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

チャート要素の実際の幅を指定します。実際の値を取得するには IChart.ValidateChartLayout() を事前に呼び出してください。 読み取り float。

**戻り値:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

チャート要素の実際の高さを指定します。実際の値を取得するには IChart.ValidateChartLayout() を事前に呼び出してください。 読み取り float。

**戻り値:**
float