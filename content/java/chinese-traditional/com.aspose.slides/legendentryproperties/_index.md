---
title: LegendEntryProperties
second_title: Aspose.Slides for Java API 參考
description: 表示圖表的圖例屬性。
type: docs
url: /zh-hant/com.aspose.slides/legendentryproperties/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties), com.aspose.slides.IDOMObject
```
public class LegendEntryProperties implements ILegendEntryProperties, IDOMObject
```

表示圖表的圖例屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getTextFormat()](#getTextFormat--) | 傳回文字格式。 |
| [getHide()](#getHide--) | 判斷圖例項目是否隱藏。 |
| [setHide(boolean value)](#setHide-boolean-) | 判斷圖例項目是否隱藏。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 傳回父圖表。 |
| [getSlide()](#getSlide--) | 傳回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回 FillFormat 的父簡報。 |
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

傳回文字格式。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**傳回值：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getHide() {#getHide--}
```
public final boolean getHide()
```

判斷圖例項目是否隱藏。可讀寫布林值。

**傳回值：**
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