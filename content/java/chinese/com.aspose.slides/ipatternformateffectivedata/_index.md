---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 不可变对象，包含有效的图案填充属性。
type: docs
url: /zh/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

不可变对象，包含有效的图案填充属性。

--------------------

此接口用作 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) 和 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | 返回图案样式。 |
| [getForeColor()](#getForeColor--) | 返回前景图案颜色。 |
| [getBackColor()](#getBackColor--) | 返回背景图案颜色。 |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | 使用指定的颜色创建图案填充的平铺图像。 |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

返回图案样式。只读 [PatternStyle](../../com.aspose.slides/patternstyle)。

**返回值:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

返回前景图案颜色。只读 java.awt.Color。

**返回值:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

返回背景图案颜色。只读 java.awt.Color。

**返回值:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

使用指定的颜色创建图案填充的平铺图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| background | java.awt.Color | 图案的背景 java.awt.Color。 |
| foreground | java.awt.Color | 图案的前景 java.awt.Color。 |

**返回值:**
[IImage](../../com.aspose.slides/iimage) - 平铺 [IImage](../../com.aspose.slides/iimage).