---
title: FillFormat
second_title: Aspose.Slides Androidra a Java API Referencián keresztül
description: A kitöltési formázási beállításokat képviseli.
type: docs
url: /hu/com.aspose.slides/fillformat/
---
**Öröklődés:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**  
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)  
```
public final class FillFormat extends PVIObject implements IFillFormat
```

A kitöltés formázási beállításait jelenti.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Visszaadja vagy beállítja a kitöltés típusát. |
| [setFillType(byte value)](#setFillType-byte-) | Visszaadja vagy beállítja a kitöltés típusát. |
| [getSolidFillColor()](#getSolidFillColor--) | Visszaadja a kitöltés színét. |
| [getGradientFormat()](#getGradientFormat--) | Visszaadja a színátmenetes kitöltés formátumát. |
| [getPatternFormat()](#getPatternFormat--) | Visszaadja a mintás kitöltés formátumát. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Visszaadja a kép kitöltés formátumát. |
| [getRotateWithShape()](#getRotateWithShape--) | Megállapítja, hogy a kitöltést az alakzattal együtt kell-e elforgatni. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Megállapítja, hogy a kitöltést az alakzattal együtt kell-e elforgatni. |
| [getEffective()](#getEffective--) | Megkapja a hatékony kitöltési formázási adatokat az öröklődés alkalmazásával. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszaadja:**  
long

### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Visszaadja vagy beállítja a kitöltés típusát. Olvasható/írható [FillType](../../com.aspose.slides/filltype).

**Visszaadja:**  
byte

### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Visszaadja vagy beállítja a kitöltés típusát. Olvasható/írható [FillType](../../com.aspose.slides/filltype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Visszaadja a kitöltés színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszaadja:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Visszaadja a színátmenetes kitöltés formátumát. Csak olvasható [IGradientFormat](../../com.aspose.slides/igradientformat).

**Visszaadja:**  
[IGradientFormat](../../com.aspose.slides/igradientformat)

### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Visszaadja a mintás kitöltés formátumát. Csak olvasható [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Visszaadja:**  
[IPatternFormat](../../com.aspose.slides/ipatternformat)

### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

Visszaadja a kép kitöltés formátumát. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszaadja:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Megállapítja, hogy a kitöltést az alakzattal együtt kell-e elforgatni. Olvasható/írható [NullableBool](../../com.aspose.slides/nullablebool).

**Visszaadja:**  
byte

### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Megállapítja, hogy a kitöltést az alakzattal együtt kell-e elforgatni. Olvasható/írható [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

Megkapja a hatékony kitöltési formázási adatokat az öröklődés alkalmazásával.

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


**Visszaadja:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).