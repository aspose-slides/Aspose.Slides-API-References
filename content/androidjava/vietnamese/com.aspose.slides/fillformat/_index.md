---
title: FillFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Mô tả một tùy chọn định dạng tô.
type: docs
url: /vi/com.aspose.slides/fillformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Mô tả một tùy chọn định dạng tô.
## Phương thức

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Trả về hoặc đặt loại tô. |
| [setFillType(byte value)](#setFillType-byte-) | Trả về hoặc đặt loại tô. |
| [getSolidFillColor()](#getSolidFillColor--) | Trả về màu tô. |
| [getGradientFormat()](#getGradientFormat--) | Trả về định dạng tô gradient. |
| [getPatternFormat()](#getPatternFormat--) | Trả về định dạng tô mẫu. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Trả về định dạng tô ảnh. |
| [getRotateWithShape()](#getRotateWithShape--) | Xác định liệu phần tô có nên quay cùng hình hay không. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Xác định liệu phần tô có nên quay cùng hình hay không. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng tô hiệu lực với kế thừa đã được áp dụng. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Phiên bản. Chỉ-đọc long.

**Giá trị trả về:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Trả về hoặc đặt loại tô. Đọc/ghi [FillType](../../com.aspose.slides/filltype).

**Giá trị trả về:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Trả về hoặc đặt loại tô. Đọc/ghi [FillType](../../com.aspose.slides/filltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Trả về màu tô. Chỉ-đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Giá trị trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Trả về định dạng tô gradient. Chỉ-đọc [IGradientFormat](../../com.aspose.slides/igradientformat).

**Giá trị trả về:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Trả về định dạng tô mẫu. Chỉ-đọc [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Giá trị trả về:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


Trả về định dạng tô ảnh. Chỉ-đọc [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Giá trị trả về:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Xác định liệu phần tô có nên quay cùng hình hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Giá trị trả về:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Xác định liệu phần tô có nên quay cùng hình hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


Lấy dữ liệu định dạng tô hiệu lực với kế thừa đã được áp dụng.

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


**Giá trị trả về:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - một [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).