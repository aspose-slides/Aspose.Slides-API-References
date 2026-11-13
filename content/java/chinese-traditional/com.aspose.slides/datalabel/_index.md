---
title: DataLabel
second_title: Aspose.Slides for Java API 參考
description: 代表系列標籤。
type: docs
url: /zh-hant/com.aspose.slides/datalabel/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

代表系列標籤。
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | 建立 DataLabel 類別的新實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父圖表。 |
| [isVisible()](#isVisible--) | False 表示資料標籤不可見（因此所有 Show\*-flags (ShowValue, ...) 均為 false）。 |
| [hide()](#hide--) | 透過將所有 Show\*-flags (ShowValue, ...) 設為 false 來隱藏資料標籤。 |
| [getActualLabelText()](#getActualLabelText--) | 返回根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值的實際標籤文字。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 使用參數 "text" 中的文字初始化 TextFrameForOverriding。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 可以包含豐富格式的文字。 |
| [getTextFormat()](#getTextFormat--) | 返回文字格式。 |
| [getX()](#getX--) | 返回或設定標題的 x 座標，作為圖表寬度的比例。 |
| [setX(float value)](#setX-float-) | 返回或設定標題的 x 座標，作為圖表寬度的比例。 |
| [getY()](#getY--) | 返回或設定標題的 y 座標，作為圖表高度的比例。 |
| [setY(float value)](#setY-float-) | 返回或設定標題的 y 座標，作為圖表高度的比例。 |
| [getWidth()](#getWidth--) | 返回或設定標題的寬度，作為圖表寬度的比例。 |
| [setWidth(float value)](#setWidth-float-) | 返回或設定標題的寬度，作為圖表寬度的比例。 |
| [getHeight()](#getHeight--) | 返回或設定標題的高度，作為圖表高度的比例。 |
| [setHeight(float value)](#setHeight-float-) | 返回或設定標題的高度，作為圖表高度的比例。 |
| [getRight()](#getRight--) | 右。 |
| [getBottom()](#getBottom--) | 底部。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | 返回資料標籤格式。 |
| [getValueFromCell()](#getValueFromCell--) | 取得或設定工作簿資料儲存格。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 取得或設定工作簿資料儲存格。 |
| [getLabelShapeType()](#getLabelShapeType--) | 取得或設定資料標籤的形狀類型。 |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | 取得或設定資料標籤的形狀類型。 |
| [getActualX()](#getActualX--) | 指定圖表元素相對於圖表左上角的實際 x 位置（左側）。 |
| [getActualY()](#getActualY--) | 指定圖表元素相對於圖表左上角的實際上側位置。 |
| [getActualWidth()](#getActualWidth--) | 指定圖表元素的實際寬度。 |
| [getActualHeight()](#getActualHeight--) | 指定圖表元素的實際高度。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父簡報。 |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```


建立 DataLabel 類別的新實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 父 ChartDataPoint。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回值：**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


返回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**返回值：**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False 表示資料標籤不可見（因此所有 Show*-flags (ShowValue, ...) 均為 false）。唯讀 boolean 。

**返回值：**
boolean
--------------------

如果資料標籤是可見的，您可以使用 Hide() 方法將其隱藏。但如果資料標籤不可見（IsVisible 為 false），您可以透過將 Show*-flags (ShowValue, ...) 設為 true 狀態來使資料標籤可見。

**返回值：**
boolean
### hide() {#hide--}
```
public final void hide()
```


透過將所有 Show*-flags (ShowValue, ...) 設為 false 來隱藏資料標籤。此後 IsVisible 將為 false。

--------------------

如果資料標籤不可見（IsVisible 為 false），您可以透過將 Show*-flags (ShowValue, ...) 設為 true 來使資料標籤可見。
### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```


返回根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值的實際標籤文字。

**返回值：**
java.lang.String - java.lang.String 物件。
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```


使用參數 "text" 中的文字初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已經初始化，則直接更改其文字。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrameForOverriding 的文字。 |

**返回值：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```


可以包含豐富格式的文字。如果此屬性不為 null，則此格式化文字值會覆寫資料標籤的自動產生文字。資料標籤的自動產生文字指的是由 ShowSeriesName、ShowValue、... 屬性管理，並以 TextFormatManager.TextFormat 屬性格式化的文字。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回值：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


返回文字格式。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回值：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```


返回或設定標題的 x 座標，作為圖表寬度的比例。讀/寫 float 。

**返回值：**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


返回或設定標題的 x 座標，作為圖表寬度的比例。讀/寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```


返回或設定標題的 y 座標，作為圖表高度的比例。讀/寫 float 。

**返回值：**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


返回或設定標題的 y 座標，作為圖表高度的比例。讀/寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```


返回或設定標題的寬度，作為圖表寬度的比例。讀/寫 float 。

**返回值：**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


返回或設定標題的寬度，作為圖表寬度的比例。讀/寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```


返回或設定標題的高度，作為圖表高度的比例。讀/寫 float 。

**返回值：**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


返回或設定標題的高度，作為圖表高度的比例。讀/寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```


右。唯讀 float 。

**返回值：**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


底部。唯讀 float 。

**返回值：**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```


返回資料標籤格式。唯讀 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**返回值：**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```


取得或設定工作簿資料儲存格。若 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true 時套用。

**返回值：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```


取得或設定工作簿資料儲存格。若 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true 時套用。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```


取得或設定資料標籤的形狀類型。如果未定義形狀，則返回 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 將第一個資料標籤的形狀類型設為 Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值：**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```


取得或設定資料標籤的形狀類型。如果未定義形狀，則返回 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 將第一個資料標籤的形狀類型設為 Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```


指定圖表元素相對於圖表左上角的實際 x 位置（左側）。在取得實際值前，請先呼叫 IChart.ValidateChartLayout() 方法。唯讀 float 。

**返回值：**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


指定圖表元素相對於圖表左上角的實際上側位置。於取得實際值前，請先呼叫 IChart.ValidateChartLayout() 方法。唯讀 float 。

**返回值：**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


指定圖表元素的實際寬度。於取得實際值前，請先呼叫 IChart.ValidateChartLayout() 方法。唯讀 float 。

**返回值：**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


指定圖表元素的實際高度。於取得實際值前，請先呼叫 IChart.ValidateChartLayout() 方法。唯讀 float 。

**返回值：**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


返回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回值：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


返回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation)