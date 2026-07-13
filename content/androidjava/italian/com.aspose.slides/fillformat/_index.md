---
title: FillFormat
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un'opzione di formattazione del riempimento.
type: docs
url: /it/com.aspose.slides/fillformat/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Rappresenta un'opzione di formattazione del riempimento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Restituisce o imposta il tipo di riempimento. |
| [setFillType(byte value)](#setFillType-byte-) | Restituisce o imposta il tipo di riempimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Restituisce il colore di riempimento. |
| [getGradientFormat()](#getGradientFormat--) | Restituisce il formato di riempimento gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Restituisce il formato di riempimento a trama. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Restituisce il formato di riempimento immagine. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se il riempimento debba essere ruotato con la forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina se il riempimento debba essere ruotato con la forma. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione del riempimento efficaci con l'ereditarietà applicata. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Sola lettura long.

**Restituisce:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Restituisce o imposta il tipo di riempimento. Lettura/Scrittura [FillType](../../com.aspose.slides/filltype).

**Restituisce:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Restituisce o imposta il tipo di riempimento. Lettura/Scrittura [FillType](../../com.aspose.slides/filltype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Restituisce il colore di riempimento. Sola lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Restituisce il formato di riempimento gradiente. Sola lettura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Restituisce:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Restituisce il formato di riempimento a trama. Sola lettura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Restituisce:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


Restituisce il formato di riempimento immagine. Sola lettura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Restituisce:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Determina se il riempimento debba essere ruotato con la forma. Lettura/Scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Determina se il riempimento debba essere ruotato con la forma. Lettura/Scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


Ottiene i dati di formattazione del riempimento efficaci con l'ereditarietà applicata.

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

**Restituisce:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Un [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).