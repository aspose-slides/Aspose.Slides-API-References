---
title: FillFormat
second_title: Aspose.Slides dla Androida za pośrednictwem interfejsu API Java
description: Reprezentuje opcje formatowania wypełnienia.
type: docs
url: /pl/com.aspose.slides/fillformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Reprezentuje opcje formatowania wypełnienia.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Zwraca lub ustawia typ wypełnienia. |
| [setFillType(byte value)](#setFillType-byte-) | Zwraca lub ustawia typ wypełnienia. |
| [getSolidFillColor()](#getSolidFillColor--) | Zwraca kolor wypełnienia. |
| [getGradientFormat()](#getGradientFormat--) | Zwraca format wypełnienia gradientowego. |
| [getPatternFormat()](#getPatternFormat--) | Zwraca format wypełnienia wzoru. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Zwraca format wypełnienia obrazu. |
| [getRotateWithShape()](#getRotateWithShape--) | Określa, czy wypełnienie powinno być obracane wraz z kształtem. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Określa, czy wypełnienie powinno być obracane wraz z kształtem. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane formatowania wypełnienia z uwzględnieniem dziedziczenia. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu, long.

**Zwraca:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Zwraca lub ustawia typ wypełnienia. Odczyt/zapis [FillType](../../com.aspose.slides/filltype).

**Zwraca:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Zwraca lub ustawia typ wypełnienia. Odczyt/zapis [FillType](../../com.aspose.slides/filltype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Zwraca kolor wypełnienia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Zwraca format wypełnienia gradientowego. Tylko do odczytu [IGradientFormat](../../com.aspose.slides/igradientformat).

**Zwraca:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Zwraca format wypełnienia wzoru. Tylko do odczytu [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Zwraca:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


Zwraca format wypełnienia obrazu. Tylko do odczytu [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Zwraca:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Określa, czy wypełnienie powinno być obracane wraz z kształtem. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Określa, czy wypełnienie powinno być obracane wraz z kształtem. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


Pobiera efektywne dane formatowania wypełnienia z uwzględnieniem dziedziczenia.

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


**Zwraca:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Obiekt [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).