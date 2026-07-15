---
title: DataLabel
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示系列標籤。
type: docs
url: /zh-hant/com.aspose.slides/datalabel/
---
**繼承：**
java.lang.Object

**全部已實作的介面：**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

表示系列標籤。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | 建立 DataLabel 類別的新實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 傳回父圖表。 |
| [isVisible()](#isVisible--) | False 表示資料標籤不可見（因此所有 Show*-flags (ShowValue, ...) 皆為 false）。 |
| [hide()](#hide--) | 透過將所有 Show*-flags (ShowValue, ...) 設為 false 狀態，使資料標籤隱藏。 |
| [getActualLabelText()](#getActualLabelText--) | 根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值傳回實際的標籤文字。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 以參數 "text" 的文字初始化 TextFrameForOverriding。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 可以包含富格式文字。 |
| [getTextFormat()](#getTextFormat--) | 傳回文字格式。 |
| [getX()](#getX--) | 傳回或設定標題的 x 座標，作為圖表寬度的比例。 |
| [setX(float value)](#setX-float-) | 傳回或設定標題的 x 座標，作為圖表寬度的比例。 |
| [getY()](#getY--) | 傳回或設定標題的 y 座標，作為圖表高度的比例。 |
| [setY(float value)](#setY-float-) | 傳回或設定標題的 y 座標，作為圖表高度的比例。 |
| [getWidth()](#getWidth--) | 傳回或設定標題的寬度，作為圖表寬度的比例。 |
| [setWidth(float value)](#setWidth-float-) | 傳回或設定標題的寬度，作為圖表寬度的比例。 |
| [getHeight()](#getHeight--) | 傳回或設定標題的高度，作為圖表高度的比例。 |
| [setHeight(float value)](#setHeight-float-) | 傳回或設定標題的高度，作為圖表高度的比例。 |
| [getRight()](#getRight--) | 右側。 |
| [getBottom()](#getBottom--) | 底部。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | 傳回資料標籤格式。 |
| [getValueFromCell()](#getValueFromCell--) | 取得或設定工作簿資料儲存格。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 取得或設定工作簿資料儲存格。 |
| [getActualX()](#getActualX--) | 指定圖表元件相對於圖表左上角的實際 x 位置（左）。 |
| [getActualY()](#getActualY--) | 指定圖表元件相對於圖表左上角的實際 y 位置（上）。 |
| [getActualWidth()](#getActualWidth--) | 指定圖表元件的實際寬度。 |
| [getActualHeight()](#getActualHeight--) | 指定圖表元件的實際高度。 |
| [getSlide()](#getSlide--) | 傳回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回 FillFormat 的父簡報。 |

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

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值：**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

傳回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**傳回值：**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False 表示資料標籤不可見（因此所有 Show*-flags (ShowValue, ...) 皆為 false）。唯讀 boolean 。

--------------------

如果資料標籤可見，您可以使用 Hide() 方法將其隱藏。但如果資料標籤不可見（IsVisible 為 false），您可以透過將 Show*-flags (ShowValue, ...) 設為 true 狀態使資料標籤可見。

**傳回值：**
boolean

### hide() {#hide--}
```
public final void hide()
```

透過將所有 Show*-flags (ShowValue, ...) 設為 false 狀態，使資料標籤隱藏。執行後 IsVisible 會變為 false。

--------------------

如果資料標籤不可見（IsVisible 為 false），您可以透過將 Show*-flags (ShowValue, ...) 設為 true 狀態使其可見。

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

傳回根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值的實際標籤文字。

**傳回值：**
java.lang.String - java.lang.String 物件。

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

以參數 "text" 的文字初始化 TextFrameForOverriding。若 TextFrameForOverriding 已初始化，則僅變更其文字。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 為新的 TextFrameForOverriding 提供的文字。 |

**傳回值：**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

可以包含富格式文字。如果此屬性不為 null，則此格式化文字會覆寫資料標籤的自動產生文字。資料標籤的自動產生文字是指由 ShowSeriesName、ShowValue、... 屬性管理，且以 TextFormatManager.TextFormat 屬性格式化的文字。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**傳回值：**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

傳回文字格式。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**傳回值：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

傳回或設定標題的 x 座標，作為圖表寬度的比例。可讀寫 float 。

**傳回值：**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

傳回或設定標題的 x 座標，作為圖表寬度的比例。可讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

傳回或設定標題的 y 座標，作為圖表高度的比例。可讀寫 float 。

**傳回值：**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

傳回或設定標題的 y 座標，作為圖表高度的比例。可讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

傳回或設定標題的寬度，作為圖表寬度的比例。可讀寫 float 。

**傳回值：**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

傳回或設定標題的寬度，作為圖表寬度的比例。可讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

傳回或設定標題的高度，作為圖表高度的比例。可讀寫 float 。

**傳回值：**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

傳回或設定標題的高度，作為圖表高度的比例。可讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

右側。唯讀 float 。

**傳回值：**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

底部。唯讀 float 。

**傳回值：**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

傳回資料標籤格式。唯讀 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**傳回值：**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

取得或設定工作簿資料儲存格。若 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true 時套用。

**傳回值：**
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

### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定圖表元件相對於圖表左上角的實際 x 位置（左）。唯讀 float 。

**傳回值：**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定圖表元件相對於圖表左上角的實際 y 位置（上）。唯讀 float 。

**傳回值：**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定圖表元件的實際寬度。唯讀 float 。

**傳回值：**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定圖表元件的實際高度。唯讀 float 。

**傳回值：**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**傳回值：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回值：**
[IPresentation](../../com.aspose.slides/ipresentation)