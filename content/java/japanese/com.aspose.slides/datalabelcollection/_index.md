---
title: DataLabelCollection
second_title: Aspose.Slides for Java API リファレンス
description: シリーズ ラベルを表します。
type: docs
url: /ja/com.aspose.slides/datalabelcollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

シリーズ ラベルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の Java イテレータを返します。 |
| [isVisible()](#isVisible--) | false は、データ ラベルがデフォルトで表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue など) が false になります)。 |
| [hide()](#hide--) | DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue など) を false に設定して、データ ラベルをデフォルトで非表示にします。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | コレクション内の表示されているデータ ラベルの数を取得します。 |
| [getCount()](#getCount--) | コレクション内のすべてのデータ ラベルの数を取得します。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | デフォルトのデータ ラベル形式を取得します。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | データ ラベルのリーダー ライン形式を表します。 |
| [getParentSeries()](#getParentSeries--) | 親シリーズを取得します。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | コレクション内で指定された DataLabel のインデックスを返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのデータ ポイントに対するデータ ラベルを取得します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |
### getChart() {#getChart--}
```
public final IChart getChart()
```

親チャートを返します。読み取り専用 [IChart](../../com.aspose.slides/ichart).

**戻り値:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

コレクション全体の Java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

false は、データ ラベルがデフォルトで表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue など) が false になります)。 読み取り専用 boolean.

--------------------

データ ラベルがデフォルトで表示されている場合、Hide() メソッドでデフォルトで非表示にできます。データ ラベルがデフォルトで表示されない場合 (IsVisible が false) は、DefaultDataLabelFormat プロパティの Show*-フラグ (ShowValue など) を true に設定して、データ ラベルを「デフォルトで表示」できるようにします。

**戻り値:**
boolean
### hide() {#hide--}
```
public final void hide()
```

DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue など) を false に設定して、データ ラベルをデフォルトで非表示にします。この操作後、IsVisible は false になります。

--------------------

データ ラベルがデフォルトで表示されない場合 (IsVisible が false) は、DefaultDataLabelFormat プロパティの Show*-フラグ (ShowValue など) を true に設定して、データ ラベルを「デフォルトで表示」できるようにします。

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
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

コレクション内で指定された DataLabel のインデックスを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 検索対象の DataLabel。 |

**戻り値:**
int - DataLabel のインデックス、またはこのコレクションに属さない場合は -1。
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

指定されたインデックスのデータ ポイントに対するデータ ラベルを取得します。

代替方法として、次のようにデータ ラベルにアクセスできます: - series.getDataPoints().get_Item(i).getLabel() - ラベルのプロパティを管理します。

**パラメータ:**
| パラメータ | 型 | 説明 |
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