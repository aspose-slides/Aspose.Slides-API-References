---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 不可變物件，包含有效的圖案填充屬性。
type: docs
url: /zh-hant/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

不可變物件，包含有效的圖案填充屬性。

--------------------

此介面用作 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) 及 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | 傳回圖案樣式。 |
| [getForeColor()](#getForeColor--) | 傳回前景圖案顏色。 |
| [getBackColor()](#getBackColor--) | 傳回背景圖案顏色。 |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | 建立具有指定顏色的圖案填充瓦片影像。 |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


傳回圖案樣式。唯讀 [PatternStyle](../../com.aspose.slides/patternstyle)。

**傳回值:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


傳回前景圖案顏色。唯讀 java.awt.Color。

**傳回值:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


傳回背景圖案顏色。唯讀 java.awt.Color。

**傳回值:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


建立具有指定顏色的圖案填充瓦片影像。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| background | java.awt.Color | 圖案的背景 java.awt.Color。 |
| foreground | java.awt.Color | 圖案的前景 java.awt.Color。 |

**傳回值:**
[IImage](../../com.aspose.slides/iimage) - 圖磚 [IImage](../../com.aspose.slides/iimage).