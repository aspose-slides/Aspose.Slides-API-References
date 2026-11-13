---
title: IDataLabel
second_title: Aspose.Slides for Java API 參考文件
description: 代表系列標籤。
type: docs
url: /zh-hant/com.aspose.slides/idatalabel/
---
**所有已實作的介面：**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

代表系列標籤。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isVisible()](#isVisible--) | False 表示資料標籤不可見（因此所有 Show*-flags（ShowValue，...）皆為 false）。 |
| [hide()](#hide--) | 透過將所有 Show*-flags（ShowValue，...）設定為 false 來隱藏資料標籤。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | 傳回資料標籤的格式。 |
| [getValueFromCell()](#getValueFromCell--) | 取得或設定工作簿資料儲存格。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 取得或設定工作簿資料儲存格。 |
| [getActualLabelText()](#getActualLabelText--) | 根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值傳回實際的標籤文字。 |
| [getLabelShapeType()](#getLabelShapeType--) | 取得或設定資料標籤的形狀類型。 |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | 取得或設定資料標籤的形狀類型。 |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False 表示資料標籤不可見（因此所有 Show*-flags（ShowValue，...）皆為 false）。唯讀 boolean.

--------------------

如果資料標籤是可見的，您可以使用 Hide() 方法將其隱藏。但如果資料標籤不可見（IsVisible 為 false），您可以透過設定 Show*-flags（ShowValue，...）為 true 來使資料標籤可見。

**傳回：**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

透過將所有 Show*-flags（ShowValue，...）設定為 false 來隱藏資料標籤。執行後 IsVisible 將為 false。

--------------------

如果資料標籤不可見（IsVisible 為 false），您可以透過設定 Show*-flags（ShowValue，...）為 true 來使資料標籤可見。

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

傳回資料標籤的格式。唯讀 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**傳回：**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

取得或設定工作簿資料儲存格。如果 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true，則套用此設定。

**傳回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

取得或設定工作簿資料儲存格。如果 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true，則套用此設定。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值傳回實際的標籤文字。

**傳回：**
java.lang.String - Actual label text String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

取得或設定資料標籤的形狀類型。如果未定義形狀，則傳回 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)。

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 設定第一個資料標籤的形狀類型為 Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回：**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

取得或設定資料標籤的形狀類型。如果未定義形狀，則傳回 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)。

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 設定第一個資料標籤的形狀類型為 Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | int |  |