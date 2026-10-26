---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API 参考
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
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | 使用指定颜色创建图案填充的瓦片图像。 |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

返回图案样式。只读 [PatternStyle](../../com.aspose.slides/patternstyle)。

**返回：**
byte

### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```

返回前景图案颜色。只读 java.lang.Integer。

**返回：**
java.lang.Integer

### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```

返回背景图案颜色。只读 java.lang.Integer。

**返回：**
java.lang.Integer

### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```

使用指定颜色创建图案填充的瓦片图像。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| background | java.lang.Integer | 图案的背景 java.lang.Integer。 |
| foreground | java.lang.Integer | 图案的前景 java.lang.Integer。 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - 瓦片 [IImage](../../com.aspose.slides/iimage).