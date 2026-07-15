---
title: ILegend
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示圖表圖例屬性。
type: docs
url: /zh-hant/com.aspose.slides/ilegend/
---
**所有已實作的介面：**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

表示圖表圖例屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getOverlay()](#getOverlay--) | 判斷其他圖表元素是否允許覆蓋圖例。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 判斷其他圖表元素是否允許覆蓋圖例。 |
| [getPosition()](#getPosition--) | 指定圖例在圖表上的位置。 |
| [setPosition(int value)](#setPosition-int-) | 指定圖例在圖表上的位置。 |
| [getFormat()](#getFormat--) | 傳回圖例的格式。 |
| [getEntries()](#getEntries--) | 取得圖例項目。 |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

判斷其他圖表元素是否允許覆蓋圖例。讀/寫布林值。

**傳回：**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

判斷其他圖表元素是否允許覆蓋圖例。讀/寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

指定圖例在圖表上的位置。非 NaN 的 X、Y、Width、Height 屬性值會覆寫此屬性的效果。讀/寫 [LegendPositionType](../../com.aspose.slides/legendpositiontype)。

**傳回：**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

指定圖例在圖表上的位置。非 NaN 的 X、Y、Width、Height 屬性值會覆寫此屬性的效果。讀/寫 [LegendPositionType](../../com.aspose.slides/legendpositiontype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

傳回圖例的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**傳回：**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

取得圖例項目。唯讀 [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)。

**傳回：**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)