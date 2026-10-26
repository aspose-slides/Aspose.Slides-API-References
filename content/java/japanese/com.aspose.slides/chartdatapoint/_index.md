---
title: ChartDataPoint
second_title: Aspose.Slides for Java API リファレンス
description: シリーズ データ ポイントを表します。
type: docs
url: /ja/com.aspose.slides/chartdatapoint/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

シリーズ データ ポイントを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | チャート データ ポイントのサイズ値を返します。 |
| [getColorValue()](#getColorValue--) | チャート データ ポイントの色の値を返します。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | カスタム値タイプの場合のシリーズ エラーバー 値を表します。 |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | バブルに 3D エフェクトが適用されていることを指定します。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | バブルに 3D エフェクトが適用されていることを指定します。 |
| [getExplosion()](#getExplosion--) | パイの中心からデータ ポイントが移動する量を指定します。 |
| [setExplosion(int value)](#setExplosion-int-) | パイの中心からデータ ポイントが移動する量を指定します。 |
| [getFormat()](#getFormat--) | 書式設定プロパティを表します。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 書式設定プロパティを表します。 |
| [getMarker()](#getMarker--) | データ マーカーを指定します。 |
| [getSetAsTotal()](#getSetAsTotal--) | データ ポイントを合計として設定します。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | データ ポイントを合計として設定します。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie の場合の対応する凡例エントリのプロパティ。 |
| [remove()](#remove--) | チャート シリーズから DataPoint を削除します。 |
| [getDataPointLevels()](#getDataPointLevels--) | データ ポイント レベルのコンテナを返します。 |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | シリーズ インデックス、データ ポイント インデックス、ParentSeriesGroup.IsColorVaried プロパティ、チャート スタイルに基づくデータ ポイントの自動カラーを返します。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | データ ポイントが負の値の場合に色を反転させるかどうかを指定します。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | データ ポイントが負の値の場合に色を反転させるかどうかを指定します。 |
| [getActualX()](#getActualX--) | チャート要素の左側位置（左）を左上隅からの相対座標で指定します。 |
| [getActualY()](#getActualY--) | チャート要素の上側位置を左上隅からの相対座標で指定します。 |
| [getActualWidth()](#getActualWidth--) | チャート要素の実際の幅を指定します。 |
| [getActualHeight()](#getActualHeight--) | チャート要素の実際の高さを指定します。 |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. 読み取り専用 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**戻り値:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. 読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. 読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. 読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

チャート データ ポイントのサイズ値を返します。Treemap および Sunburst チャートで使用されます。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

チャート データ ポイントの色の値を返します。Map チャートで使用されます。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

カスタム値タイプの場合のシリーズ エラーバー 値を表します。読み取り専用 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**戻り値:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. 読み取り専用 [IDataLabel](../../com.aspose.slides/idatalabel)。

**戻り値:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

バブルに 3D エフェクトが適用されていることを指定します。読み書き boolean。

**戻り値:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

バブルに 3D エフェクトが適用されていることを指定します。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

パイの中心からデータ ポイントが移動する量を指定します。読み書き int。

**戻り値:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

パイの中心からデータ ポイントが移動する量を指定します。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

書式設定プロパティを表します。読み書き [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

書式設定プロパティを表します。読み書き [IFormat](../../com.aspose.slides/iformat)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

データ マーカーを指定します。読み取り専用 [IMarker](../../com.aspose.slides/imarker)。

**戻り値:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

データ ポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。

**戻り値:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

データ ポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie の場合の対応する凡例エントリのプロパティ。読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

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

データ ポイント レベルのコンテナを返します。Treeamp と Sunburst 系列に適用されます。データ ポイント レベルのインデックスは 0 から始まります。

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

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

シリーズ インデックス、データ ポイント インデックス、ParentSeriesGroup.IsColorVaried プロパティ、チャート スタイルに基づくデータ ポイントの自動カラーを返します。この色は FillType が NotDefined の場合にデフォルトで使用されます。

**戻り値:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

データ ポイントが負の値の場合に色を反転させるかどうかを指定します。読み書き boolean。

**戻り値:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

データ ポイントが負の値の場合に色を反転させるかどうかを指定します。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

チャート要素の左側位置（左）を左上隅からの相対座標で指定します。実際の値を取得するには IChart.ValidateChartLayout() を呼び出してください。読み取り float。

**戻り値:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

チャート要素の上側位置を左上隅からの相対座標で指定します。実際の値を取得するには IChart.ValidateChartLayout() を呼び出してください。読み取り float。

**戻り値:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

チャート要素の実際の幅を指定します。実際の値を取得するには IChart.ValidateChartLayout() を呼び出してください。読み取り float。

**戻り値:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

チャート要素の実際の高さを指定します。実際の値を取得するには IChart.ValidateChartLayout() を呼び出してください。読み取り float。

**戻り値:**
float