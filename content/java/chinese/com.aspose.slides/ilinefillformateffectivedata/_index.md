---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides Java API 参考
description: 不可变对象，包含有效的线条填充属性。
type: docs
url: /zh/com.aspose.slides/ilinefillformateffectivedata/
---
**所有实现的接口：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

不可变对象，包含有效的线条填充属性。

--------------------

此接口用作 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillType()](#getFillType--) | 返回填充类型。 |
| [getSolidFillColor()](#getSolidFillColor--) | 返回实心填充的颜色。 |
| [getGradientFormat()](#getGradientFormat--) | 返回渐变填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 返回图案填充格式。 |
| [getRotateWithShape()](#getRotateWithShape--) | 确定是否应随形状旋转填充。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


返回填充类型。只读 [FillType](../../com.aspose.slides/filltype)。

**返回:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


返回实心填充的颜色。只读 java.awt.Color。

**返回:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


返回渐变填充格式。只读 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)。

**返回:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


返回图案填充格式。只读 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)。

**返回:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


确定是否应随形状旋转填充。只读 boolean。

**返回:**
boolean