---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 表示用于填充形状的图案。
type: docs
url: /zh/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

表示用于填充形状的图案。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | 返回或设置图案样式。 |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | 返回或设置图案样式。 |
| [getForeColor()](#getForeColor--) | 返回前景图案颜色。 |
| [getBackColor()](#getBackColor--) | 返回背景图案颜色。 |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | 使用指定颜色创建图案填充的平铺图像。 |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | 创建图案填充的平铺图像。 |

### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

返回或设置图案样式。读/写 [PatternStyle](../../com.aspose.slides/patternstyle)。

**返回:**
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

返回或设置图案样式。读/写 [PatternStyle](../../com.aspose.slides/patternstyle)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

返回前景图案颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

返回背景图案颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

使用指定颜色创建图案填充的平铺图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| background | java.lang.Integer | 图案的背景 java.lang.Integer。 |
| foreground | java.lang.Integer | 图案的前景 java.lang.Integer。 |

**返回:**
[IImage](../../com.aspose.slides/iimage) - 平铺 android.graphics.Bitmap。

### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

创建图案填充的平铺图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| styleColor | java.lang.Integer | 默认的 java.lang.Integer，定义于 ShapeEx 的 StyleEx 对象。填充颜色可能取决于此。 |

**返回:**
[IImage](../../com.aspose.slides/iimage) - 平铺 android.graphics.Bitmap。