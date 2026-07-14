---
title: FillFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 채우기 서식 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/fillformat/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**모든 구현 인터페이스:**  
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)  
```
public final class FillFormat extends PVIObject implements IFillFormat
```

채우기 서식 옵션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | 채우기 유형을 반환하거나 설정합니다. |
| [setFillType(byte value)](#setFillType-byte-) | 채우기 유형을 반환하거나 설정합니다. |
| [getSolidFillColor()](#getSolidFillColor--) | 채우기 색상을 반환합니다. |
| [getGradientFormat()](#getGradientFormat--) | 그라디언트 채우기 형식을 반환합니다. |
| [getPatternFormat()](#getPatternFormat--) | 패턴 채우기 형식을 반환합니다. |
| [getPictureFillFormat()](#getPictureFillFormat--) | 그림 채우기 형식을 반환합니다. |
| [getRotateWithShape()](#getRotateWithShape--) | 채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 채우기 서식 데이터를 가져옵니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

채우기 유형을 반환하거나 설정합니다. 읽기/쓰기 [FillType](../../com.aspose.slides/filltype).

**반환:**  
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

채우기 유형을 반환하거나 설정합니다. 읽기/쓰기 [FillType](../../com.aspose.slides/filltype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

채우기 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

그라디언트 채우기 형식을 반환합니다. 읽기 전용 [IGradientFormat](../../com.aspose.slides/igradientformat).

**반환:**  
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

패턴 채우기 형식을 반환합니다. 읽기 전용 [IPatternFormat](../../com.aspose.slides/ipatternformat).

**반환:**  
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

그림 채우기 형식을 반환합니다. 읽기 전용 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**반환:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

채우기가 도형과 함께 회전해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

상속이 적용된 효과적인 채우기 서식 데이터를 가져옵니다.

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


**반환:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - 하나의 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).