---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: 表示用於填充形狀的圖樣。
type: docs
url: /zh-hant/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

表示用於填充形狀的圖樣。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | 返回或設定圖樣樣式。 |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | 返回或設定圖樣樣式。 |
| [getForeColor()](#getForeColor--) | 返回前景圖樣顏色。 |
| [getBackColor()](#getBackColor--) | 返回背景圖樣顏色。 |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | 建立具有指定顏色的圖樣填充平鋪圖像。 |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | 建立圖樣填充的平鋪圖像。 |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

返回或設定圖樣樣式。讀寫 [PatternStyle](../../com.aspose.slides/patternstyle)。

**Returns:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

返回或設定圖樣樣式。讀寫 [PatternStyle](../../com.aspose.slides/patternstyle)。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

返回前景圖樣顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

返回背景圖樣顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

建立具有指定顏色的圖樣填充平鋪圖像。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| background | java.awt.Color | 圖樣的背景 java.awt.Color。 |
| foreground | java.awt.Color | 圖樣的前景 java.awt.Color。 |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

建立圖樣填充的平鋪圖像。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| styleColor | java.awt.Color | 預設的 java.awt.Color，定義於 ShapeEx 的 StyleEx 物件。填充的顏色可能取決於此。 |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.