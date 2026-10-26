---
title: LineFillFormat
second_title: Aspose.Slides for Java API 参考
description: 表示线条填充的属性。
type: docs
url: /zh/com.aspose.slides/linefillformat/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

表示线条填充的属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | 返回或设置填充类型。 |
| [setFillType(byte value)](#setFillType-byte-) | 返回或设置填充类型。 |
| [getRotateWithShape()](#getRotateWithShape--) | 确定填充是否应随形状旋转。 |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 确定填充是否应随形状旋转。 |
| [getSolidFillColor()](#getSolidFillColor--) | 返回纯色填充的颜色。 |
| [getGradientFormat()](#getGradientFormat--) | 返回渐变填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 返回图案填充格式。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long.

**返回:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

返回或设置填充类型。读/写 [FillType](../../com.aspose.slides/filltype)。

**返回:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

返回或设置填充类型。读/写 [FillType](../../com.aspose.slides/filltype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

确定填充是否应随形状旋转。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

确定填充是否应随形状旋转。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

返回纯色填充的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

返回渐变填充格式。只读 [IGradientFormat](../../com.aspose.slides/igradientformat)。

**返回:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

返回图案填充格式。只读 [IPatternFormat](../../com.aspose.slides/ipatternformat)。

**返回:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)