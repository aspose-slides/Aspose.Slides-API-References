---
title: LegendEntryProperties
second_title: Aspose.Slides for Android via Java API 參考
description: 表示圖表圖例的屬性。
type: docs
url: /zh-hant/com.aspose.slides/legendentryproperties/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties), com.aspose.slides.IDOMObject  
```
public class LegendEntryProperties implements ILegendEntryProperties, IDOMObject
```

表示圖表圖例的屬性。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getTextFormat()](#getTextFormat--) | 回傳文字格式。 |
| [getHide()](#getHide--) | 判斷圖例項目是否隱藏。 |
| [setHide(boolean value)](#setHide-boolean-) | 判斷圖例項目是否隱藏。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 回傳父圖表。 |
| [getSlide()](#getSlide--) | 回傳 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 回傳 FillFormat 的父簡報。 |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

回傳文字格式。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**回傳：**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getHide() {#getHide--}
```
public final boolean getHide()
```

判斷圖例項目是否隱藏。可讀寫布林值。

**回傳：**  
boolean

### setHide(boolean value) {#setHide-boolean-}
```
public final void setHide(boolean value)
```

判斷圖例項目是否隱藏。可讀寫布林值。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

回傳 Parent_Immediate 物件。唯讀 IDOMObject。

**回傳：**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

回傳父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**回傳：**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

回傳 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**回傳：**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

回傳 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**回傳：**  
[IPresentation](../../com.aspose.slides/ipresentation)