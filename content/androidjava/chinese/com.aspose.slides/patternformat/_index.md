---
title: PatternFormat
second_title: Aspose.Slides Android 通过 Java API 参考
description: 表示用于填充形状的图案。
type: docs
url: /zh/com.aspose.slides/patternformat/
---

**继承：**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口：**  
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)  
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

表示用于填充形状的图案。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | 返回或设置图案样式。 |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | 返回或设置图案样式。 |
| [getForeColor()](#getForeColor--) | 返回前景图案颜色。 |
| [getBackColor()](#getBackColor--) | 返回背景图案颜色。 |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | 使用指定颜色创建图案填充的平铺图像。 |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | 创建图案填充的平铺图像。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**  
long

### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

返回或设置图案样式。读写 [PatternStyle](../../com.aspose.slides/patternstyle)。

**返回：**  
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

返回或设置图案样式。读写 [PatternStyle](../../com.aspose.slides/patternstyle)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

返回前景图案颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

返回背景图案颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

使用指定颜色创建图案填充的平铺图像。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| background | java.lang.Integer | 图案的背景 java.lang.Integer。 |
| foreground | java.lang.Integer | 图案的前景 java.lang.Integer。 |

**返回：**  
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage)

### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

创建图案填充的平铺图像。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| styleColor | java.lang.Integer | 默认的 java.lang.Integer |

**返回：**  
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage)