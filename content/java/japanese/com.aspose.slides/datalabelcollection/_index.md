---
title: DataLabelCollection
second_title: Aspose.Slides for Java API リファレンス
description: シリーズラベルを表します。
type: docs
url: /ja/com.aspose.slides/datalabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

シリーズラベルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [isVisible()](#isVisible--) | False は、データ ラベルがデフォルトで表示されないことを意味し、DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue など) が false になります。 |
| [hide()](#hide--) | DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue など) を false に設定して、データ ラベルをデフォルトで非表示にします。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | コレクション内の表示可能なデータ ラベルの数を取得します。 |
| [getCount()](#getCount--) | コレクション内のすべてのデータ ラベルの数を取得します。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | デフォルトのデータ ラベル形式を取得します。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | データ ラベルのリーダー ライン形式を表します。 |
| [getParentSeries()](#getParentSeries--) | 親系列を取得します。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | コレクション内の指定された DataLabel のインデックスを返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスを持つデータ ポイントのデータ ラベルを取得します。 |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | データ ラベルのデフォルト シェイプ タイプを取得または設定します。 |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | データ ラベルのデフォルト シェイプ タイプを取得または設定します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |
### getChart() {#getChart--}
```
public final IChart getChart()
```


親チャートを返します。読み取り専用 [IChart](../../com.aspose.slides/ichart)。

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


コレクションを反復処理する列挙子を返します。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


コレクション全体の java イテレータを返します。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - コレクション全体の java.util.Iterator。
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False は、データ ラベルがデフォルトで表示されないことを意味し、DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue など) が false になることを示します。読み取り専用 boolean。

--------------------

データ ラベルがデフォルトで表示されている場合は、Hide() メソッドでデフォルトで非表示にできます。データ ラベルがデフォルトで表示されない場合 (IsVisible が false) は、DefaultDataLabelFormat プロパティの Show*-フラグ (ShowValue など) を true に設定して、デフォルトで「表示」にできます。

**Returns:**
boolean
### hide() {#hide--}
```
public final void hide()
```


DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue など) を false に設定して、データ ラベルをデフォルトで非表示にします。これにより IsVisible は false になります。

--------------------

データ ラベルがデフォルトで表示されない場合 (IsVisible が false) は、DefaultDataLabelFormat プロパティの Show*-フラグ (ShowValue など) を true に設定して、デフォルトで「表示」にできます。

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


コレクション内の表示可能なデータ ラベルの数を取得します。読み取り専用 int。

**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


コレクション内のすべてのデータ ラベルの数を取得します。読み取り専用 int。

**Returns:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


デフォルトのデータ ラベル形式を取得します。読み取り専用 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**Returns:**
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

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```


親系列を取得します。読み取り専用 [IChartSeries](../../com.aspose.slides/ichartseries)。

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


コレクション内の指定された DataLabel のインデックスを返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 見つける DataLabel。 |

**Returns:**
int - DataLabel のインデックス、またはこのコレクションに属さない場合は -1。
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


指定されたインデックスを持つデータ ポイントのデータ ラベルを取得します。

--------------------

データ ラベルへの代替アクセス方法: - series.getDataPoints().get_Item(i).getLabel() - ラベル プロパティを管理します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```


データ ラベルのデフォルト シェイプ タイプを取得または設定します。シェイプが定義されていない場合は [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) を返します。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 最初のシリーズのすべてのデータラベルのシェイプタイプをEllipseに設定します。
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

このプロパティを設定すると、コレクション内のすべてのデータ ラベルの IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) プロパティも同じ値に設定されます。

**Returns:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```


データ ラベルのデフォルト シェイプ タイプを取得または設定します。シェイプが定義されていない場合は [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) を返します。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 最初のシリーズのすべてのデータラベルのシェイプタイプをEllipseに設定します。
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

このプロパティを設定すると、コレクション内のすべてのデータ ラベルの IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) プロパティも同じ値に設定されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


FillFormat の親スライドを返します。読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide)。

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


FillFormat の親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)