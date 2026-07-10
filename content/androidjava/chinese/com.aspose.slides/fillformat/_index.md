---
title: FillFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 表示填充格式选项。
type: docs
url: /zh/com.aspose.slides/fillformat/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口：**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

表示填充格式选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | 返回或设置填充类型。 |
| [setFillType(byte value)](#setFillType-byte-) | 返回或设置填充类型。 |
| [getSolidFillColor()](#getSolidFillColor--) | 返回填充颜色。 |
| [getGradientFormat()](#getGradientFormat--) | 返回渐变填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 返回图案填充格式。 |
| [getPictureFillFormat()](#getPictureFillFormat--) | 返回图片填充格式。 |
| [getRotateWithShape()](#getRotateWithShape--) | 确定填充是否应随形状旋转。 |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 确定填充是否应随形状旋转。 |
| [getEffective()](#getEffective--) | 获取已应用继承的有效填充格式数据。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

返回或设置填充类型。读/写 [FillType](../../com.aspose.slides/filltype)。

**返回：**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

返回或设置填充类型。读/写 [FillType](../../com.aspose.slides/filltype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

返回填充颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

返回渐变填充格式。只读 [IGradientFormat](../../com.aspose.slides/igradientformat)。

**返回：**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

返回图案填充格式。只读 [IPatternFormat](../../com.aspose.slides/ipatternformat)。

**返回：**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

返回图片填充格式。只读 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

确定填充是否应随形状旋转。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

确定填充是否应随形状旋转。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

获取已应用继承的有效填充格式数据。

--------------------

> ```
> This example demonstrates getting shape's effective fill format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IFillFormatEffectiveData effectiveFillFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getFillFormat().getEffective();
>  	System.out.println("Type: " + effectiveFillFormat.getFillType());
>  	switch (effectiveFillFormat.getFillType())
>  	{
>  		case FillType.Solid:
>  			System.out.println("Fill color: " + effectiveFillFormat.getSolidFillColor());
>  			break;
>  		case FillType.Pattern:
>  			System.out.println("Pattern style: " + effectiveFillFormat.getPatternFormat().getPatternStyle());
>  			System.out.println("Fore color: " + effectiveFillFormat.getPatternFormat().getForeColor());
>  			System.out.println("Back color: " + effectiveFillFormat.getPatternFormat().getBackColor());
>  			break;
>  		case FillType.Gradient:
>  			System.out.println("Gradient direction: " + effectiveFillFormat.getGradientFormat().getGradientDirection());
>  			System.out.println("Gradient stops count: " + effectiveFillFormat.getGradientFormat().getGradientStops().size());
>  			break;
>  		case FillType.Picture:
>  			System.out.println("Picture width: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getWidth());
>  			System.out.println("Picture height: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getHeight());
>  			break;
>  	}
>  } finally {
>   if (pres != != null) pres.dispose();
>  }
> ```

**返回：**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).