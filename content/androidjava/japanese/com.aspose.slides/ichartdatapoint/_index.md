---
title: IChartDataPoint
second_title: Aspose.Slides for Android の Java API リファレンス
description: シリーズのデータ ポイントを表します。
type: docs
url: /ja/com.aspose.slides/ichartdatapoint/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

シリーズのデータ ポイントを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getXValue()](#getXValue--) | チャート データ ポイントの x 値を返します。 |
| [getYValue()](#getYValue--) | チャート データ ポイントの y 値を返します。 |
| [getBubbleSize()](#getBubbleSize--) | チャート データ ポイントのバブル サイズを返します。 |
| [getValue()](#getValue--) | チャート データ ポイントの値を返します。 |
| [getSizeValue()](#getSizeValue--) | チャート データ ポイントのサイズ値を返します。 |
| [getColorValue()](#getColorValue--) | チャート データ ポイントのカラー値を返します。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | カスタム値タイプの場合のシリーズ誤差棒値を表します。 |
| [getLabel()](#getLabel--) | チャート データ ポイントのラベルを表します。 |
| [isBubble3D()](#isBubble3D--) | バブルに 3-D 効果が適用されていることを指定します。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | バブルに 3-D 効果が適用されていることを指定します。 |
| [getExplosion()](#getExplosion--) | データ ポイントが円グラフの中心から移動する量を指定します。 |
| [setExplosion(int value)](#setExplosion-int-) | データ ポイントが円グラフの中心から移動する量を指定します。 |
| [getFormat()](#getFormat--) | 書式設定プロパティを表します。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 書式設定プロパティを表します。 |
| [getMarker()](#getMarker--) | データ マーカーを指定します。 |
| [remove()](#remove--) | チャート シリーズから DataPoint を削除します。 |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | シリーズインデックス、データ ポイント インデックス、ParentSeriesGroup.IsColorVaried プロパティ、およびチャート スタイルに基づくデータ ポイントの自動カラーを返します。FillType が NotDefined の場合、このカラーがデフォルトで使用されます。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | このリストのチャート タイプの場合の対応する凡例エントリのプロパティ: ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie。 |
| [getSetAsTotal()](#getSetAsTotal--) | データ ポイントを合計として設定します。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | データ ポイントを合計として設定します。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 値が負の場合、データ ポイントが色を反転させることを指定します。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 値が負の場合、データ ポイントが色を反転させることを指定します。 |
| [getDataPointLevels()](#getDataPointLevels--) | データ ポイント レベルのコンテナを返します。 |
| [getIndex()](#getIndex--) | このデータ ポイントが適用される親の子コレクションを決定します。 |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

チャート データ ポイントの x 値を返します。読み取り専用 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)。

**戻り値:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

チャート データ ポイントの y 値を返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

チャート データ ポイントのバブル サイズを返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

チャート データ ポイントの値を返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

チャート データ ポイントのサイズ値を返します。Treemap および Sunburst チャートで使用されます。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

チャート データ ポイントのカラー値を返します。Map チャートで使用されます。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

カスタム値タイプの場合のシリーズ誤差棒値を表します。読み取り専用 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**戻り値:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

チャート データ ポイントのラベルを表します。読み取り専用 [IDataLabel](../../com.aspose.slides/idatalabel)。

**戻り値:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

バブルに 3-D 効果が適用されていることを指定します。読み書き可能な boolean。

**戻り値:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

バブルに 3-D 効果が適用されていることを指定します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

データ ポイントが円グラフの中心から移動する量を指定します。読み書き可能な int。

**戻り値:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

データ ポイントが円グラフの中心から移動する量を指定します。読み書き可能な int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

書式設定プロパティを表します。読み書き可能な [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

書式設定プロパティを表します。読み書き可能な [IFormat](../../com.aspose.slides/iformat)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

データ マーカーを指定します。読み取り専用 [IMarker](../../com.aspose.slides/imarker)。

**戻り値:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

チャート シリーズから DataPoint を削除します。

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

シリーズインデックス、データ ポイント インデックス、ParentSeriesGroup.IsColorVaried プロパティ、およびチャート スタイルに基づくデータ ポイントの自動カラーを返します。このカラーは FillType が NotDefined の場合、デフォルトで使用されます。

**戻り値:**
java.lang.Integer - Automatic color of data point java.lang.Integer

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

このリストのチャート タイプの場合の対応する凡例エントリのプロパティ: ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie。読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

データ ポイントを合計として設定します。Waterfall シリーズ タイプにのみ適用されます。

**戻り値:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

データ ポイントを合計として設定します。Waterfall シリーズ タイプにのみ適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

値が負の場合、データ ポイントが色を反転させることを指定します。読み書き可能な boolean。

**戻り値:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

値が負の場合、データ ポイントが色を反転させることを指定します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

データ ポイント レベルのコンテナを返します。Treeamp および Sunburst シリーズに適用されます。データ ポイント レベルのインデックスはゼロベースです。

**戻り値:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

このデータ ポイントが適用される親の子コレクションを決定します。読み取り専用 long。

**戻り値:**
long