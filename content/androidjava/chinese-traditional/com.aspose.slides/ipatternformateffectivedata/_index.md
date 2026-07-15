---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /zh-hant/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

不可變對象，包含有效的圖案填充屬性。

--------------------

This interface is used as a part of [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) and [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


返回圖案樣式。唯讀 [PatternStyle](../../com.aspose.slides/patternstyle)。

**返回:**  
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


返回前景圖案顏色。唯讀 java.lang.Integer。

**返回:**  
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


返回背景圖案顏色。唯讀 java.lang.Integer。

**返回:**  
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


建立具有指定顏色的圖案填充平鋪圖像。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| background | java.lang.Integer | 圖案的背景 java.lang.Integer。 |
| foreground | java.lang.Integer | 圖案的前景 java.lang.Integer。 |

**返回:**  
[IImage](../../com.aspose.slides/iimage) - 磁磚 [IImage](../../com.aspose.slides/iimage).