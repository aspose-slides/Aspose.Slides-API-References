---
title: DataTable
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示資料表屬性。
type: docs
url: /zh-hant/com.aspose.slides/datatable/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有實作的介面:**  
[com.aspose.slides.IDataTable](../../com.aspose.slides/idatatable)  
```
public class DataTable extends DomObject<Chart> implements IDataTable
```

表示資料表屬性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) | 返回物件的線條、填充和效果樣式。 |
| [hasBorderHorizontal()](#hasBorderHorizontal--) | 如果圖表資料表具有水平儲存格邊框則為 true。 |
| [setBorderHorizontal(boolean value)](#setBorderHorizontal-boolean-) | 如果圖表資料表具有水平儲存格邊框則為 true。 |
| [hasBorderOutline()](#hasBorderOutline--) | 如果圖表資料表具有外框邊框則為 true。 |
| [setBorderOutline(boolean value)](#setBorderOutline-boolean-) | 如果圖表資料表具有外框邊框則為 true。 |
| [hasBorderVertical()](#hasBorderVertical--) | 如果圖表資料表具有垂直儲存格邊框則為 true。 |
| [setBorderVertical(boolean value)](#setBorderVertical-boolean-) | 如果圖表資料表具有垂直儲存格邊框則為 true。 |
| [getShowLegendKey()](#getShowLegendKey--) | 如果資料標籤圖例鍵可見則為 true。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 如果資料標籤圖例鍵可見則為 true。 |
| [getChart()](#getChart--) | 返回圖表。 |
| [getTextFormat()](#getTextFormat--) | 返回文字格式。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父簡報。 |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


返回物件的線條、填充和效果樣式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**返回:**  
[IFormat](../../com.aspose.slides/iformat)

### hasBorderHorizontal() {#hasBorderHorizontal--}
```
public final boolean hasBorderHorizontal()
```


如果圖表資料表具有水平儲存格邊框則為 true。可讀寫 boolean。

**返回:**  
boolean

### setBorderHorizontal(boolean value) {#setBorderHorizontal-boolean-}
```
public final void setBorderHorizontal(boolean value)
```


如果圖表資料表具有水平儲存格邊框則為 true。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasBorderOutline() {#hasBorderOutline--}
```
public final boolean hasBorderOutline()
```


如果圖表資料表具有外框邊框則為 true。可讀寫 boolean。

**返回:**  
boolean

### setBorderOutline(boolean value) {#setBorderOutline-boolean-}
```
public final void setBorderOutline(boolean value)
```


如果圖表資料表具有外框邊框則為 true。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasBorderVertical() {#hasBorderVertical--}
```
public final boolean hasBorderVertical()
```


如果圖表資料表具有垂直儲存格邊框則為 true。可讀寫 boolean。

**返回:**  
boolean

### setBorderVertical(boolean value) {#setBorderVertical-boolean-}
```
public final void setBorderVertical(boolean value)
```


如果圖表資料表具有垂直儲存格邊框則為 true。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```


如果資料標籤圖例鍵可見則為 true。可讀寫 boolean。

**返回:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```


如果資料標籤圖例鍵可見則為 true。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```


返回圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**返回:**  
[IChart](../../com.aspose.slides/ichart)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


返回文字格式。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


返回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


返回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**  
[IPresentation](../../com.aspose.slides/ipresentation)