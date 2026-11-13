---
title: IDataLabelCollection
second_title: Aspose.Slides の Java API リファレンス
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
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのデータポイントのデータラベルを取得します。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | コレクション内のすべてのデータラベルのデフォルト形式を返します。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | データラベルのリーダーライン形式を表します。 |
| [isVisible()](#isVisible--) | False は、データラベルがデフォルトで表示されないことを意味します（そのため DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) が false になります）。 |
| [hide()](#hide--) | DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) を false に設定することで、データラベルをデフォルトで非表示にします。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | コレクション内の表示されているデータラベルの数を取得します。 |
| [getCount()](#getCount--) | コレクション内のすべてのデータラベルの数を取得します。 |
| [getParentSeries()](#getParentSeries--) | 親チャートシリーズを返します。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | コレクション内の指定された DataLabel のインデックスを返します。 |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | データラベルのデフォルトのシェイプタイプを取得または設定します。 |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | データラベルのデフォルトのシェイプタイプを取得または設定します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


指定されたインデックスのデータポイントのデータラベルを取得します。

--------------------

データラベルにアクセスする別の方法は次のとおりです: - getSeries().getDataPoints().get_Item(i).getLabel() - ラベルプロパティを管理します。

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


コレクション内のすべてのデータラベルのデフォルト形式を返します。読み取り専用 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**戻り値:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


データラベルのリーダーライン形式を表します。読み取り専用 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

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


False は、データラベルがデフォルトで表示されないことを意味します（そのため DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) が false になります）。読み取り専用 boolean 。

--------------------

データラベルがデフォルトで表示されている場合は、Hide() メソッドでデフォルトで非表示にできます。ただしデータラベルがデフォルトで表示されない場合（IsVisible が false）には、DefaultDataLabelFormat プロパティの Show*-フラグ (ShowValue, ...) を true に設定することで「デフォルトで表示」させることができます。

**戻り値:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) を false に設定することで、データラベルをデフォルトで非表示にします。これにより IsVisible は false になります。

--------------------

データラベルがデフォルトで表示されない場合（IsVisible が false）には、DefaultDataLabelFormat プロパティの Show*-フラグ (ShowValue, ...) を true に設定することで「デフォルトで表示」させることができます。

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


コレクション内の表示されているデータラベルの数を取得します。読み取り専用  int .

**戻り値:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


コレクション内のすべてのデータラベルの数を取得します。読み取り専用  int .

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
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 見つける DataLabel。 |

**戻り値:**
int - DataLabel のインデックス、またはこのコレクションに属さない場合は -1
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```


データラベルのデフォルトのシェイプタイプを取得または設定します。シェイプが定義されていない場合は [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) を返します。

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

このプロパティを設定すると、コレクション内のすべてのデータラベルの IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) プロパティも同じ値に設定されます。

**戻り値:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```


データラベルのデフォルトのシェイプタイプを取得または設定します。シェイプが定義されていない場合は [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) を返します。

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

このプロパティを設定すると、コレクション内のすべてのデータラベルの IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) プロパティも同じ値に設定されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |