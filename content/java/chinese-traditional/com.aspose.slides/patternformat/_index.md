---
title: PatternFormat
second_title: Aspose.Slides for Java API 參考
description: 表示用於填充形狀的圖案。
type: docs
url: /zh-hant/com.aspose.slides/patternformat/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**全部已實作的介面：**
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
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | 使用指定的顏色建立圖案填充的瓦片影像。 |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | 建立圖案填充的瓦片影像。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回：**
long

### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

返回或設定圖案樣式。讀寫 [PatternStyle](../../com.aspose.slides/patternstyle)。

**返回：**
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

返回或設定圖案樣式。讀寫 [PatternStyle](../../com.aspose.slides/patternstyle)。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

返回前景圖案顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

返回背景圖案顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

使用指定的顏色建立圖案填充的瓦片影像。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| background | java.awt.Color | 圖案的背景 java.awt.Color。 |
| foreground | java.awt.Color | 圖案的前景 java.awt.Color。 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - 瓦片 [IImage](../../com.aspose.slides/iimage)。

### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

建立圖案填充的瓦片影像。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| styleColor | java.awt.Color | 預設的 java.awt.Color |

**返回：**
[IImage](../../com.aspose.slides/iimage) - 瓦片 [IImage](../../com.aspose.slides/iimage)。