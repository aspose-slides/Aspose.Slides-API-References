---
title: IDataLabelCollection
second_title: Aspose.Slides for Java API リファレンス
description: シリーズ ラベルを表します。
type: docs
url: /ja/com.aspose.slides/idatalabelcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

シリーズのラベルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定したインデックスのデータ ポイントのデータ ラベルを取得します。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | コレクション内のすべてのデータ ラベルの既定の書式を返します。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | データ ラベルのリーダー ラインの書式を表します。 |
| [isVisible()](#isVisible--) | false の場合、デフォルトでデータ ラベルは表示されません (したがって DefaultDataLabelFormat プロパティのすべての Show\*-フラグ (ShowValue, ...) は false です)。 |
| [hide()](#hide--) | DefaultDataLabelFormat プロパティのすべての Show\*-フラグ (ShowValue, ...) を false に設定して、デフォルトでデータ ラベルを非表示にします。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | コレクション内の表示されているデータ ラベルの数を取得します。 |
| [getCount()](#getCount--) | コレクション内のすべてのデータ ラベルの数を取得します。 |
| [getParentSeries()](#getParentSeries--) | 親チャート シリーズを返します。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | コレクション内の指定された DataLabel のインデックスを返します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


指定したインデックスのデータ ポイントのデータ ラベルを取得します。

--------------------

データ ラベルにアクセスする別の方法は次のとおりです。- getSeries().getDataPoints().get_Item(i).getLabel() - ラベル プロパティを管理します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


コレクション内のすべてのデータ ラベルの既定の書式を返します。読み取り専用 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**戻り値:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


データ ラベルのリーダー ラインの書式を表します。読み取り専用 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


false の場合、デフォルトでデータ ラベルは表示されません (したがって DefaultDataLabelFormat プロパティのすべての Show\*-フラグ (ShowValue, ...) は false です)。読み取り専用 boolean 。

--------------------

デフォルトでデータ ラベルが表示される場合は、Hide() メソッドでデフォルトで非表示にできます。ただしデフォルトで表示されない場合 (IsVisible が false) は、DefaultDataLabelFormat プロパティの Show\*-フラグ (ShowValue, ...) を true に設定して「デフォルトで表示」状態にできます。

**戻り値:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


DefaultDataLabelFormat プロパティのすべての Show\*-フラグ (ShowValue, ...) を false に設定して、デフォルトでデータ ラベルを非表示にします。これ以降 IsVisible は false になります。

--------------------

デフォルトでデータ ラベルが表示されない場合 (IsVisible が false) は、DefaultDataLabelFormat プロパティの Show\*-フラグ (ShowValue, ...) を true に設定して「デフォルトで表示」状態にできます。

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


コレクション内の表示されているデータ ラベルの数を取得します。読み取り専用 int 。

**戻り値:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


コレクション内のすべてのデータ ラベルの数を取得します。読み取り専用 int 。

**戻り値:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


親チャート シリーズを返します。読み取り専用 [IChartSeries](../../com.aspose.slides/ichartseries)。

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


コレクション内の指定された DataLabel のインデックスを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 検索する DataLabel。 |

**戻り値:**
int - DataLabel のインデックス、またはこのコレクションに含まれない場合は -1。