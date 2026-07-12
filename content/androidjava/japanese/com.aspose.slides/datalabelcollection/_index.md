---
title: DataLabelCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: シリーズラベルを表します。
type: docs
url: /ja/com.aspose.slides/datalabelcollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
``` 
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

シリーズラベルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [isVisible()](#isVisible--) | False はデータ ラベルが既定で表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) が false になります)。 |
| [hide()](#hide--) | すべての Show*-フラグ (ShowValue, ...) を false に設定して、データ ラベルを既定で非表示にします。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | コレクション内の表示されているデータ ラベルの数を取得します。 |
| [getCount()](#getCount--) | コレクション内のすべてのデータ ラベルの数を取得します。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | デフォルトのデータ ラベル形式を取得します。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | データ ラベルのリーダー ライン形式を表します。 |
| [getParentSeries()](#getParentSeries--) | 親シリーズを取得します。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | コレクション内の指定された DataLabel のインデックスを返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定したインデックスのデータ ポイントに対するデータ ラベルを取得します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |
### getChart() {#getChart--}
```
public final IChart getChart()
```


親チャートを返します。読み取り専用 [IChart](../../com.aspose.slides/ichart)。

**戻り値:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


コレクションを反復する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - コレクションを反復するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False はデータ ラベルが既定で表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) が false になります)。読み取り専用 boolean。

--------------------

データ ラベルが既定で表示されている場合は、Hide() メソッドで既定で非表示にすることができます。データ ラベルが既定で表示されていない場合 (IsVisible が false) は、DefaultDataLabelFormat プロパティの Show*-フラグ (ShowValue, ...) を true に設定することで「既定で表示」にすることができます。

**戻り値:**
boolean
### hide() {#hide--}
```
public final void hide()
```


すべての Show*-フラグ (ShowValue, ...) を false に設定して、データ ラベルを既定で非表示にします。これにより IsVisible は false になります。

--------------------

データ ラベルが既定で表示されていない場合 (IsVisible が false) は、DefaultDataLabelFormat プロパティの Show*-フラグ (ShowValue, ...) を true に設定することで「既定で表示」にできます。

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


コレクション内の表示されているデータ ラベルの数を取得します。読み取り専用 int。

**戻り値:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


コレクション内のすべてのデータ ラベルの数を取得します。読み取り専用 int。

**戻り値:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


デフォルトのデータ ラベル形式を取得します。読み取り専用 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**戻り値:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```


データ ラベルのリーダー ライン形式を表します。読み取り専用 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```


親シリーズを取得します。読み取り専用 [IChartSeries](../../com.aspose.slides/ichartseries)。

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


コレクション内の指定された DataLabel のインデックスを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 検索対象の DataLabel。 |

**戻り値:**
int - DataLabel のインデックス、またはこのコレクションに属さない場合は -1。
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


指定したインデックスのデータ ポイントに対応するデータ ラベルを取得します。

--------------------

データ ラベルへの代替アクセス方法は次のとおりです: - series.getDataPoints().get_Item(i).getLabel() - ラベル プロパティを管理します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IDataLabel](../../com.aspose.slides/idatalabel)
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