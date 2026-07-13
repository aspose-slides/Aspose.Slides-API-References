---
title: FillFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een vulopmaakoptie voor.
type: docs
url: /nl/com.aspose.slides/fillformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Stelt opties voor vulopmaak voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Geeft het type vulling terug of stelt het in. |
| [setFillType(byte value)](#setFillType-byte-) | Geeft het type vulling terug of stelt het in. |
| [getSolidFillColor()](#getSolidFillColor--) | Geeft de vulkleur terug. |
| [getGradientFormat()](#getGradientFormat--) | Geeft het verloop vulformaat terug. |
| [getPatternFormat()](#getPatternFormat--) | Geeft het patroon vulformaat terug. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Geeft het afbeelding vulformaat terug. |
| [getRotateWithShape()](#getRotateWithShape--) | Bepaalt of de vulling mee moet draaien met de vorm. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bepaalt of de vulling mee moet draaien met de vorm. |
| [getEffective()](#getEffective--) | Haalt effectieve vulopmaakgegevens op met de toegepaste overerving. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Geeft het type vulling terug of stelt het in. Lezen/Schrijven [FillType](../../com.aspose.slides/filltype).

**Retour:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Geeft het type vulling terug of stelt het in. Lezen/Schrijven [FillType](../../com.aspose.slides/filltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Geeft de vulkleur terug. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Geeft het verloop vulformaat terug. Alleen-lezen [IGradientFormat](../../com.aspose.slides/igradientformat).

**Retour:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Geeft het patroon vulformaat terug. Alleen-lezen [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Retour:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


Geeft het afbeelding vulformaat terug. Alleen-lezen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retour:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Bepaalt of de vulling mee moet draaien met de vorm. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Bepaalt of de vulling mee moet draaien met de vorm. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


Haalt effectieve vulopmaakgegevens op met de toegepaste overerving.

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


**Retour:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).