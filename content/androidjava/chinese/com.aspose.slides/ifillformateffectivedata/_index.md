---
title: IFillFormatEffectiveData
second_title: Aspose.Slides for Android via Java API 参考文档
description: 不可变对象，包含有效的填充格式属性。
type: docs
url: /zh/com.aspose.slides/ifillformateffectivedata/
---
**所有实现的接口：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

不可变对象，包含有效的填充格式属性。

--------------------

此接口与 [IFillFormat](../../com.aspose.slides/ifillformat) 接口一起使用，以返回应用继承后的有效格式值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillType()](#getFillType--) | 返回填充类型。 |
| [getSolidFillColor()](#getSolidFillColor--) | 返回填充颜色。 |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | 获取颜色方案定义的填充颜色。 |
| [getGradientFormat()](#getGradientFormat--) | 返回渐变填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 返回图案填充格式。 |
| [getPictureFillFormat()](#getPictureFillFormat--) | 返回图片填充格式。 |
| [getRotateWithShape()](#getRotateWithShape--) | 确定填充是否应随形状旋转。 |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

返回填充类型。只读 [FillType](../../com.aspose.slides/filltype)。

**返回：**
byte

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

返回填充颜色。只读 java.lang.Integer。

**返回：**
java.lang.Integer

### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

获取颜色方案定义的填充颜色。[SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) 值表示 SolidFillColor (\#getSolidFillColor.getSolidFillColor) 不是方案颜色。只读 [SchemeColor](../../com.aspose.slides/schemecolor)。

**返回：**
int

### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

返回渐变填充格式。只读 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)。

**返回：**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)

### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

返回图案填充格式。只读 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)。

**返回：**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)

### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

返回图片填充格式。只读 [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)。

**返回：**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)

### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

确定填充是否应随形状旋转。只读 boolean。

**返回：**
boolean