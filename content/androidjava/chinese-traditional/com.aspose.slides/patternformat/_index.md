---
title: PatternFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示用於填充形狀的圖案。
type: docs
url: /zh-hant/com.aspose.slides/patternformat/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面：**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

表示用於填充形狀的圖案。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | 返回或設定圖案樣式。 |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | 返回或設定圖案樣式。 |
| [getForeColor()](#getForeColor--) | 返回前景圖案顏色。 |
| [getBackColor()](#getBackColor--) | 返回背景圖案顏色。 |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | 建立具有指定顏色的圖案填充圖塊影像。 |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | 建立圖案填充的圖塊影像。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**回傳值：**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

返回或設定圖案樣式。讀寫 [PatternStyle](../../com.aspose.slides/patternstyle)。

**回傳值：**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

返回或設定圖案樣式。讀寫 [PatternStyle](../../com.aspose.slides/patternstyle)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

返回前景圖案顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**回傳值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

返回背景圖案顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**回傳值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

建立具有指定顏色的圖案填充圖塊影像。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| background | java.lang.Integer | 圖案的背景 java.lang.Integer。 |
| foreground | java.lang.Integer | 圖案的前景 java.lang.Integer。 |

**回傳值：**
[IImage](../../com.aspose.slides/iimage) - 圖塊 [IImage](../../com.aspose.slides/iimage)。
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

建立圖案填充的圖塊影像。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| styleColor | java.lang.Integer | 預設的 java.lang.Integer |

**回傳值：**
[IImage](../../com.aspose.slides/iimage) - 圖塊 [IImage](../../com.aspose.slides/iimage)。