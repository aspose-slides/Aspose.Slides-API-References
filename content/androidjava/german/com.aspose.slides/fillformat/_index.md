---
title: FillFormat
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt Optionen für die Füllformatierung dar.
type: docs
url: /de/com.aspose.slides/fillformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Stellt Optionen für die Füllformatierung dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Gibt den Typ der Füllung zurück oder legt ihn fest. |
| [setFillType(byte value)](#setFillType-byte-) | Gibt den Typ der Füllung zurück oder legt ihn fest. |
| [getSolidFillColor()](#getSolidFillColor--) | Gibt die Füllfarbe zurück. |
| [getGradientFormat()](#getGradientFormat--) | Gibt das Farbverlauf-Füllformat zurück. |
| [getPatternFormat()](#getPatternFormat--) | Gibt das Muster-Füllformat zurück. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Gibt das Bild-Füllformat zurück. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestimmt, ob die Füllung mit der Form gedreht werden soll. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bestimmt, ob die Füllung mit der Form gedreht werden soll. |
| [getEffective()](#getEffective--) | Ermittelt effektive Füllformatierungsdaten mit angewandter Vererbung. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur-Lese long.

**Rückgabe:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Gibt den Typ der Füllung zurück oder legt ihn fest. Lese/Schreib [FillType](../../com.aspose.slides/filltype).

**Rückgabe:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Gibt den Typ der Füllung zurück oder legt ihn fest. Lese/Schreib [FillType](../../com.aspose.slides/filltype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Gibt die Füllfarbe zurück. Nur-Lese [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Gibt das Farbverlauf-Füllformat zurück. Nur-Lese [IGradientFormat](../../com.aspose.slides/igradientformat).

**Rückgabe:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Gibt das Muster-Füllformat zurück. Nur-Lese [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Rückgabe:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


Gibt das Bild-Füllformat zurück. Nur-Lese [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Rückgabe:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Bestimmt, ob die Füllung mit der Form gedreht werden soll. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Bestimmt, ob die Füllung mit der Form gedreht werden soll. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


Ermittelt effektive Füllformatierungsdaten mit angewandter Vererbung.

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

**Rückgabe:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - ein [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).