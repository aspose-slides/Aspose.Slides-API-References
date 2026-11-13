---
title: ChartDataPoint
second_title: Aspose.Slides for Java API リファレンス
description: シリーズのデータポイントを表します。
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

シリーズのデータポイントを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getXValue()](#getXValue--) | XValue。 |
| [getYValue()](#getYValue--) | YValue。 |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize。 |
| [getValue()](#getValue--) | Value。 |
| [getSizeValue()](#getSizeValue--) | チャート データポイントのサイズ値を返します。 |
| [getColorValue()](#getColorValue--) | チャート データポイントの色値を返します。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Custom 値タイプの場合のシリーズエラーバーの値を表します。 |
| [getLabel()](#getLabel--) | ラベル。 |
| [isBubble3D()](#isBubble3D--) | バブルに 3-D 効果が適用されていることを指定します。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | バブルに 3-D 効果が適用されていることを指定します。 |
| [getExplosion()](#getExplosion--) | 円グラフの中心からデータポイントを移動させる量を指定します。 |
| [setExplosion(int value)](#setExplosion-int-) | 円グラフの中心からデータポイントを移動させる量を指定します。 |
| [getFormat()](#getFormat--) | 書式設定プロパティを表します。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 書式設定プロパティを表します。 |
| [getMarker()](#getMarker--) | データ マーカーを指定します。 |
| [getSetAsTotal()](#getSetAsTotal--) | データポイントを合計として設定します。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | データポイントを合計として設定します。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie のチャートタイプの場合の対応する凡例エントリのプロパティ。 |
| [remove()](#remove--) | チャートシリーズから DataPoint を削除します。 |
| [getDataPointLevels()](#getDataPointLevels--) | データポイント レベルのコンテナを返します。 |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | シリーズインデックス、データポイントインデックス、ParentSeriesGroup.IsColorVaried プロパティ、およびチャートスタイルに基づくデータポイントの自動カラーを返します。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 値が負の場合、データポイントは色を反転させることを指定します。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 値が負の場合、データポイントは色を反転させることを指定します。 |
| [getCachedValue()](#getCachedValue--) | キャッシュされたチャート データポイントの値を取得します。 |
| [getCachedXValue()](#getCachedXValue--) | キャッシュされたチャート データポイントの X 値を取得します。 |
| [getCachedYValue()](#getCachedYValue--) | キャッシュされたチャート データポイントの Y 値を取得します。 |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | キャッシュされたチャート データポイントのバブルサイズを取得します。 |
| [getActualX()](#getActualX--) | チャート要素の実際の x 位置（左）を、チャートの左上隅に対して指定します。 |
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

チャート データポイントのサイズ値を返します。 Treemap と Sunburst チャートで使用されます。 読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

チャート データポイントの色値を返します。 Map チャートで使用されます。 読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Custom 値タイプの場合のシリーズエラーバーの値を表します。 読み取り専用 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**戻り値:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

ラベル。 読み取り専用 [IDataLabel](../../com.aspose.slides/idatalabel)。

**戻り値:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

バブルに 3-D 効果が適用されていることを指定します。 読み書き boolean。

**戻り値:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

バブルに 3-D 効果が適用されていることを指定します。 読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

円グラフの中心からデータポイントを移動させる量を指定します。 読み書き int。

**戻り値:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

円グラフの中心からデータポイントを移動させる量を指定します。 読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

書式設定プロパティを表します。 読み書き [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

書式設定プロパティを表します。 読み書き [IFormat](../../com.aspose.slides/iformat)。

**パラメーター:**
| パラメーター | 型 | 説明 |
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

データポイントを合計として設定します。 Waterfall 系列タイプにのみ適用されます。

**戻り値:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

データポイントを合計として設定します。 Waterfall 系列タイプにのみ適用されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie のチャートタイプの場合の対応する凡例エントリのプロパティ。 読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

チャートシリーズから DataPoint を削除します。

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

データポイント レベルのコンテナを返します。 Treeamp と Sunburst 系列に適用されます。 データポイント レベルのインデックスは 0 ベースです。

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
public final Color getAutomaticDataPointColor()
```

シリーズインデックス、データポイントインデックス、ParentSeriesGroup.IsColorVaried プロパティ、およびチャートスタイルに基づくデータポイントの自動カラーを返します。このカラーは FillType が NotDefined の場合にデフォルトで使用されます。

**戻り値:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

値が負の場合、データポイントは色を反転させることを指定します。 読み書き boolean。

**戻り値:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

値が負の場合、データポイントは色を反転させることを指定します。 読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

キャッシュされたチャート データポイントの値を取得します。 読み取り専用 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // チャートシリーズのすべてのキャッシュされた値を出力します。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

キャッシュされたチャート データポイントの X 値を取得します。 読み取り専用 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // チャートシリーズのすべてのキャッシュされた X 値を出力します。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

キャッシュされたチャート データポイントの Y 値を取得します。 読み取り専用 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // チャートシリーズのすべてのキャッシュされた Y 値を出力します。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

キャッシュされたチャート データポイントのバブルサイズを取得します。 読み取り専用 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // チャート系列のすべてのキャッシュされたバブルサイズ値を出力します。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

チャート要素の実際の x 位置（左）を、チャートの左上隅に対して指定します。 実際の値を取得するには IChart.ValidateChartLayout() を呼び出してください。 読み float。

**戻り値:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

チャート要素の実際の上位置を、チャートの左上隅に対して指定します。 実際の値を取得するには IChart.ValidateChartLayout() を呼び出してください。 読み float。

**戻り値:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

チャート要素の実際の幅を指定します。 実際の値を取得するには IChart.ValidateChartLayout() を呼び出してください。 読み float。

**戻り値:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

チャート要素の実際の高さを指定します。 実際の値を取得するには IChart.ValidateChartLayout() を呼び出してください。 読み float。

**戻り値:**
float