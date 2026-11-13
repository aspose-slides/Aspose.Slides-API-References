---
title: IChartDataPoint
second_title: Aspose.Slides for Java API リファレンス
description: シリーズ データポイントを表します。
type: docs
url: /ja/com.aspose.slides/ichartdatapoint/
---
**すべての実装インターフェイス:**  
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

シリーズ データポイントを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getXValue()](#getXValue--) | チャート データポイントの X 値を取得します。 |
| [getYValue()](#getYValue--) | チャート データポイントの Y 値を取得します。 |
| [getBubbleSize()](#getBubbleSize--) | チャート データポイントのバブル サイズを取得します。 |
| [getValue()](#getValue--) | チャート データポイントの値を取得します。 |
| [getCachedXValue()](#getCachedXValue--) | チャート データポイントのキャッシュされた X 値を取得します。 |
| [getCachedYValue()](#getCachedYValue--) | チャート データポイントのキャッシュされた Y 値を取得します。 |
| [getCachedValue()](#getCachedValue--) | チャート データポイントのキャッシュされた値を取得します。 |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | チャート データポイントのキャッシュされたバブル サイズを取得します。 |
| [getSizeValue()](#getSizeValue--) | チャート データポイントのサイズ値を取得します。 |
| [getColorValue()](#getColorValue--) | チャート データポイントのカラー値を取得します。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | カスタム値タイプの場合のシリーズ エラーバー値を表します。 |
| [getLabel()](#getLabel--) | チャート データポイントのラベルを表します。 |
| [isBubble3D()](#isBubble3D--) | バブルに 3D エフェクトが適用されていることを指定します。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | バブルに 3D エフェクトが適用されていることを指定します。 |
| [getExplosion()](#getExplosion--) | データポイントが円グラフの中心から移動する量を指定します。 |
| [setExplosion(int value)](#setExplosion-int-) | データポイントが円グラフの中心から移動する量を指定します。 |
| [getFormat()](#getFormat--) | 書式設定プロパティを表します。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 書式設定プロパティを表します。 |
| [getMarker()](#getMarker--) | データ マーカーを指定します。 |
| [remove()](#remove--) | データポイントをチャートシリーズから削除します。 |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | シリーズインデックス、データポイントインデックス、ParentSeriesGroup.IsColorVaried プロパティ、チャートスタイルに基づくデータポイントの自動カラーを返します。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 次のリストのチャートタイプの場合の対応する凡例エントリのプロパティ: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。 |
| [getSetAsTotal()](#getSetAsTotal--) | データポイントを合計として設定します。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | データポイントを合計として設定します。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 値が負の場合、データポイントの色を反転させることを指定します。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 値が負の場合、データポイントの色を反転させることを指定します。 |
| [getDataPointLevels()](#getDataPointLevels--) | データポイントレベルのコンテナを返します。 |
| [getIndex()](#getIndex--) | このデータポイントが適用される親の子コレクションを決定します。 |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

チャート データポイントの X 値を取得します。読み取り専用 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)。

**戻り値:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

チャート データポイントの Y 値を取得します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

チャート データポイントのバブル サイズを取得します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

チャート データポイントの値を取得します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

チャート データポイントのキャッシュされた X 値を取得します。読み取り専用 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

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
```

**戻り値:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

チャート データポイントのキャッシュされた Y 値を取得します。読み取り専用 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

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
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

チャート データポイントのキャッシュされた値を取得します。読み取り専用 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

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
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

チャート データポイントのキャッシュされたバブル サイズを取得します。読み取り専用 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // チャートシリーズのすべてのキャッシュされたバブルサイズ値を出力します。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

チャート データポイントのサイズ値を取得します。Treemap および Sunburst チャートで使用されます。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

チャート データポイントのカラー値を取得します。Map チャートで使用されます。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

カスタム値タイプの場合のシリーズ エラーバー値を表します。読み取り専用 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**戻り値:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

チャート データポイントのラベルを表します。読み取り専用 [IDataLabel](../../com.aspose.slides/idatalabel)。

**戻り値:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

バブルに 3D エフェクトが適用されていることを指定します。読み書き可能な boolean。

**戻り値:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

バブルに 3D エフェクトが適用されていることを指定します。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

データポイントが円グラフの中心から移動する量を指定します。読み書き可能な int。

**戻り値:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

データポイントが円グラフの中心から移動する量を指定します。読み書き可能な int。

**パラメーター:**
| パラメーター | 型 | 説明 |
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

**パラメーター:**
| パラメーター | 型 | 説明 |
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

データポイントをチャートシリーズから削除します。

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

シリーズインデックス、データポイントインデックス、ParentSeriesGroup.IsColorVaried プロパティ、チャートスタイルに基づくデータポイントの自動カラーを返します。FillType が NotDefined の場合、このカラーがデフォルトで使用されます。

**戻り値:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

次のリストのチャートタイプの場合の対応する凡例エントリのプロパティ: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

データポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。

**戻り値:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

データポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

値が負の場合、データポイントの色を反転させることを指定します。読み書き可能な boolean。

**戻り値:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

値が負の場合、データポイントの色を反転させることを指定します。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

データポイントレベルのコンテナを返します。Treeamp および Sunburst 系列に適用されます。データポイントレベルのインデックスはゼロベースです。

**戻り値:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

このデータポイントが適用される親の子コレクションを決定します。読み取り専用 long。

**戻り値:**
long