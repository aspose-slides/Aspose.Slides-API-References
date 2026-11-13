---
title: IDataLabel
second_title: Aspose.Slides for Java API リファレンス
description: シリーズのラベルを表します。
type: docs
url: /ja/com.aspose.slides/idatalabel/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridingText, IActualLayout
```

シリーズのラベルを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [isVisible()](#isVisible--) | False はデータ ラベルが表示されないことを意味します (そのためすべての Show*-フラグ (ShowValue, ...) は false です)。 |
| [hide()](#hide--) | すべての Show*-フラグ (ShowValue, ...) を false に設定してデータ ラベルを非表示にします。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | データ ラベルの書式を返します。 |
| [getValueFromCell()](#getValueFromCell--) | ワークブック データ セルを取得または設定します。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | ワークブック データ セルを取得または設定します。 |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat 設定または TextFrameForOverriding.Text の値に基づいて実際のラベル テキストを返します。 |
| [getLabelShapeType()](#getLabelShapeType--) | データ ラベルのシェイプ タイプを取得または設定します。 |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | データ ラベルのシェイプ タイプを取得または設定します。 |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False はデータ ラベルが表示されないことを意味します (そのためすべての Show*-フラグ (ShowValue, ...) は false です)。読み取り専用の boolean。

--------------------

データ ラベルが表示されている場合は Hide() メソッドで非表示にできます。データ ラベルが表示されていない場合 (IsVisible が false) は、Show*-フラグ (ShowValue, ...) を true に設定して表示できます。

**戻り値:**
boolean

### hide() {#hide--}
```
public abstract void hide()
```

すべての Show*-フラグ (ShowValue, ...) を false に設定してデータ ラベルを非表示にします。この操作後、IsVisible は false になります。

--------------------

データ ラベルが表示されていない場合 (IsVisible が false) は、Show*-フラグ (ShowValue, ...) を true に設定して表示できます。

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

データ ラベルの書式を返します。読み取り専用 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**戻り値:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

ワークブック データ セルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

ワークブック データ セルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

DataLabelFormat 設定または TextFrameForOverriding.Text の値に基づいて実際のラベル テキストを返します。

**戻り値:**
java.lang.String - 実際のラベル テキスト文字列

### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

データ ラベルのシェイプ タイプを取得または設定します。シェイプが定義されていない場合は [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) を返します。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 最初のデータラベルのシェイプタイプをEllipseに設定します。
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
int

### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

データ ラベルのシェイプ タイプを取得または設定します。シェイプが定義されていない場合は [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) を返します。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 最初のデータラベルのシェイプタイプをEllipseに設定します。
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |