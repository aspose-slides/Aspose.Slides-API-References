---
title: IFillFormat
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示填充格式选项。
type: docs
url: /zh/com.aspose.slides/ifillformat/
---
**所有实现的接口：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

表示填充格式选项。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillType()](#getFillType--) | 返回或设置填充类型。 |
| [setFillType(byte value)](#setFillType-byte-) | 返回或设置填充类型。 |
| [getSolidFillColor()](#getSolidFillColor--) | 返回填充颜色。 |
| [getGradientFormat()](#getGradientFormat--) | 返回渐变填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 返回图案填充格式。 |
| [getPictureFillFormat()](#getPictureFillFormat--) | 返回图片填充格式。 |
| [getRotateWithShape()](#getRotateWithShape--) | 确定填充是否应随形状旋转。 |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 确定填充是否应随形状旋转。 |
| [getEffective()](#getEffective--) | 获取在应用继承后有效的填充格式数据。 |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

返回或设置填充类型。可读写 [FillType](../../com.aspose.slides/filltype)。

**返回：**
byte

### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

返回或设置填充类型。可读写 [FillType](../../com.aspose.slides/filltype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

返回填充颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

返回渐变填充格式。只读 [IGradientFormat](../../com.aspose.slides/igradientformat)。

**返回：**
[IGradientFormat](../../com.aspose.slides/igradientformat)

### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

返回图案填充格式。只读 [IPatternFormat](../../com.aspose.slides/ipatternformat)。

**返回：**
[IPatternFormat](../../com.aspose.slides/ipatternformat)

### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

返回图片填充格式。只读 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

确定填充是否应随形状旋转。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

确定填充是否应随形状旋转。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

获取在应用继承后有效的填充格式数据。

**返回：**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - 一个 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).