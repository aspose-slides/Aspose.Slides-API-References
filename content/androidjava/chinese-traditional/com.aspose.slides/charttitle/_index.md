---
title: ChartTitle
second_title: Aspose.Slides for Android 的 Java API 參考
description: 代表圖表標題屬性。
type: docs
url: /zh-hant/com.aspose.slides/charttitle/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IChartTitle](../../com.aspose.slides/icharttitle), com.aspose.slides.IDOMObject
```
public class ChartTitle implements IChartTitle, IDOMObject
```

代表圖表標題屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getX()](#getX--) | 返回或設定標題的 X 坐標，以圖表寬度的比例表示。 |
| [setX(float value)](#setX-float-) | 返回或設定標題的 X 坐標，以圖表寬度的比例表示。 |
| [getY()](#getY--) | 返回或設定標題的 Y 坐標，以圖表高度的比例表示。 |
| [setY(float value)](#setY-float-) | 返回或設定標題的 Y 坐標，以圖表高度的比例表示。 |
| [getWidth()](#getWidth--) | 返回或設定標題的寬度，以圖表寬度的比例表示。 |
| [setWidth(float value)](#setWidth-float-) | 返回或設定標題的寬度，以圖表寬度的比例表示。 |
| [getHeight()](#getHeight--) | 返回或設定標題的高度，以圖表高度的比例表示。 |
| [setHeight(float value)](#setHeight-float-) | 返回或設定標題的高度，以圖表高度的比例表示。 |
| [getRight()](#getRight--) | 右。 |
| [getBottom()](#getBottom--) | 底部。 |
| [getOverlay()](#getOverlay--) | 判斷是否允許其他圖表元素與標題重疊。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 判斷是否允許其他圖表元素與標題重疊。 |
| [getFormat()](#getFormat--) | 返回標題的填充、線條、效果樣式。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 使用參數 "text" 的文字初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已經初始化，則僅更改其文字。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 可以包含富格式文字。 |
| [getTextFormat()](#getTextFormat--) | 返回文字格式。 |
| [getActualX()](#getActualX--) | 指定圖表元素相對於圖表左上角的實際 X 位置（左）。 |
| [getActualY()](#getActualY--) | 指定圖表元素相對於圖表左上角的實際上緣位置。 |
| [getActualWidth()](#getActualWidth--) | 指定圖表元素的實際寬度。 |
| [getActualHeight()](#getActualHeight--) | 指定圖表元素的實際高度。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父圖表。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父簡報。 |
### getX() {#getX--}
```
public final float getX()
```

返回或設定標題的 X 坐標，以圖表寬度的比例表示。可讀寫 float。

**回傳：**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

返回或設定標題的 X 坐標，以圖表寬度的比例表示。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

返回或設定標題的 Y 坐標，以圖表高度的比例表示。可讀寫 float。

**回傳：**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

返回或設定標題的 Y 坐標，以圖表高度的比例表示。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

返回或設定標題的寬度，以圖表寬度的比例表示。可讀寫 float。

**回傳：**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

返回或設定標題的寬度，以圖表寬度的比例表示。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

返回或設定標題的高度，以圖表高度的比例表示。可讀寫 float。

**回傳：**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

返回或設定標題的高度，以圖表高度的比例表示。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

右。唯讀 float。

**回傳：**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

底部。唯讀 float。

**回傳：**
float
### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```

判斷是否允許其他圖表元素與標題重疊。可讀寫 boolean。

**回傳：**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```

判斷是否允許其他圖表元素與標題重疊。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

返回標題的填充、線條、效果樣式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**回傳：**
[IFormat](../../com.aspose.slides/iformat)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

使用參數 "text" 的文字初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已經初始化，則僅更改其文字。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrameForOverriding 的文字。 |

**回傳：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

可以包含富格式文字。如果此屬性不為 null，則此格式化文字值會覆寫自動產生的文字。自動產生的文字是資料標籤、值軸的顯示單位標籤、軸標題、圖表標題、趨勢線的標籤的隱含屬性。自動產生的文字使用 IFormattedTextContainer.TextFormat 屬性進行格式設定。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**回傳：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

返回文字格式。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**回傳：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定圖表元素相對於圖表左上角的實際 X 位置（左）。在取得實際值之前，請先呼叫 IChart.validateChartLayout() 方法。唯讀 float。

**回傳：**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定圖表元素相對於圖表左上角的實際上緣位置。在取得實際值之前，請先呼叫 IChart.validateChartLayout() 方法。唯讀 float。

**回傳：**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定圖表元素的實際寬度。在取得實際值之前，請先呼叫 IChart.validateChartLayout() 方法。唯讀 float。

**回傳：**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定圖表元素的實際高度。在取得實際值之前，請先呼叫 IChart.validateChartLayout() 方法。唯讀 float。

**回傳：**
float
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**回傳：**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**回傳：**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**回傳：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**回傳：**
[IPresentation](../../com.aspose.slides/ipresentation)