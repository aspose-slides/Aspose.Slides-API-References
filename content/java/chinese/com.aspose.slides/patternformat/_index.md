---
title: PatternFormat
second_title: Aspose.Slides Java API 参考
description: 表示用于填充形状的图案。
type: docs
url: /zh/com.aspose.slides/patternformat/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已实现的接口：**
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
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | 使用指定颜色创建图案填充的平铺图像。 |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | 创建图案填充的平铺图像。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回值：**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

返回或设置图案样式。读/写 [PatternStyle](../../com.aspose.slides/patternstyle)。

**返回值：**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

返回或设置图案样式。读/写 [PatternStyle](../../com.aspose.slides/patternstyle)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

返回前景图案颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

返回背景图案颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

使用指定颜色创建图案填充的平铺图像。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| background | java.awt.Color | 图案的背景 java.awt.Color。 |
| foreground | java.awt.Color | 图案的前景 java.awt.Color。 |

**返回值：**
[IImage](../../com.aspose.slides/iimage) - 平铺 [IImage](../../com.aspose.slides/iimage)。
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

创建图案填充的平铺图像。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| styleColor | java.awt.Color | 默认的 java.awt.Color |

**返回值：**
[IImage](../../com.aspose.slides/iimage) - 平铺 [IImage](../../com.aspose.slides/iimage).