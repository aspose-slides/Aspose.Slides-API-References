---
title: IDataLabelCollection
second_title: Java APIリファレンスによる Android 用 Aspose.Slides
description: シリーズラベルを表します。
type: docs
url: /ja/com.aspose.slides/idatalabelcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

シリーズラベルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのデータ ポイントのデータ ラベルを取得します。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | コレクション内のすべてのデータ ラベルのデフォルト形式を返します。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | データ ラベルのリーダーライン形式を表します。 |
| [isVisible()](#isVisible--) | False は、データ ラベルがデフォルトで表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) が false になります)。 |
| [hide()](#hide--) | DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) を false に設定して、データ ラベルをデフォルトで非表示にします。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | コレクション内の表示されているデータ ラベルの数を取得します。 |
| [getCount()](#getCount--) | コレクション内のすべてのデータ ラベルの数を取得します。 |
| [getParentSeries()](#getParentSeries--) | 親チャートシリーズを返します。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | コレクション内の指定された DataLabel のインデックスを返します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

指定されたインデックスのデータ ポイントのデータ ラベルを取得します。

--------------------

代替方法として、データ ラベルにアクセスする手段は次のとおりです: - getSeries().getDataPoints().get\_Item(i).getLabel() - ラベル プロパティを管理します。

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

コレクション内のすべてのデータ ラベルのデフォルト形式を返します。読み取り専用 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**戻り値:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

データ ラベルのリーダーライン形式を表します。読み取り専用 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False は、データ ラベルがデフォルトで表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) が false になります)。読み取り専用 boolean 。

--------------------

データ ラベルがデフォルトで表示されている場合は、Hide() メソッドでデフォルトで非表示にできます。データ ラベルがデフォルトで表示されていない場合 (IsVisible が false) は、DefaultDataLabelFormat プロパティの Show*-フラグ (ShowValue, ...) を true に設定することで「デフォルトで表示」にすることができます。

**戻り値:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) を false に設定して、データ ラベルをデフォルトで非表示にします。この操作の後、IsVisible は false になります。

--------------------

データ ラベルがデフォルトで表示されていない場合 (IsVisible が false) は、DefaultDataLabelFormat プロパティの Show*-フラグ (ShowValue, ...) を true に設定することで「デフォルトで表示」にできます。

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

親チャートシリーズを返します。読み取り専用 [IChartSeries](../../com.aspose.slides/ichartseries)。

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
int - DataLabel のインデックス、またはコレクションに属さない場合は -1。