---
title: FillFormat
second_title: Aspose.Slides for Java API 參考
description: 表示填充格式選項。
type: docs
url: /zh-hant/com.aspose.slides/fillformat/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面：**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

表示填充格式選項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Returns or sets the type of filling. |
| [setFillType(byte value)](#setFillType-byte-) | Returns or sets the type of filling. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the fill color. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returns the picture fill format. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with shape. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determines whether the fill should be rotated with shape. |
| [getEffective()](#getEffective--) | Gets effective fill formatting data with the inheritance applied. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


版本。唯讀 long.

**傳回：**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Returns or sets the type of filling. Read/write [FillType](../../com.aspose.slides/filltype).

**傳回：**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Returns or sets the type of filling. Read/write [FillType](../../com.aspose.slides/filltype).

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Returns the fill color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Returns the gradient fill format. Read-only [IGradientFormat](../../com.aspose.slides/igradientformat).

**傳回：**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Returns the pattern fill format. Read-only [IPatternFormat](../../com.aspose.slides/ipatternformat).

**傳回：**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


Returns the picture fill format. Read-only [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**傳回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Determines whether the fill should be rotated with shape. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**傳回：**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Determines whether the fill should be rotated with shape. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


取得套用繼承後的有效填充格式資料。

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
>   if (pres != null) pres.dispose();
>  }
> ```


**傳回：**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).