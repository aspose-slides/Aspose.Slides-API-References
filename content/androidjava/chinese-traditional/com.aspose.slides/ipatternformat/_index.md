---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示用於填充形狀的圖案。
type: docs
url: /zh-hant/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

表示用於填充形狀的圖案。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | 返回或設定圖案樣式。 |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | 返回或設定圖案樣式。 |
| [getForeColor()](#getForeColor--) | 返回前景圖案顏色。 |
| [getBackColor()](#getBackColor--) | 返回背景圖案顏色。 |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | 使用指定顏色建立圖案填充的瓦片圖像。 |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | 建立圖案填充的瓦片圖像。 |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

返回或設定圖案樣式。可讀寫 [PatternStyle](../../com.aspose.slides/patternstyle)。

**返回:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

返回或設定圖案樣式。可讀寫 [PatternStyle](../../com.aspose.slides/patternstyle)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

返回前景圖案顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

返回背景圖案顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

使用指定顏色建立圖案填充的瓦片圖像。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| background | java.lang.Integer | 圖案的背景 java.lang.Integer。 |
| foreground | java.lang.Integer | 圖案的前景 java.lang.Integer。 |

**返回:**
[IImage](../../com.aspose.slides/iimage) - 瓦片 android.graphics.Bitmap。
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

建立圖案填充的瓦片圖像。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| styleColor | java.lang.Integer | 預設的 java.lang.Integer，定義於 ShapeEx 的 StyleEx 物件。填充的顏色可能取決於此。 |

**返回:**
[IImage](../../com.aspose.slides/iimage) - 瓦片 android.graphics.Bitmap。