---
title: FillFormat
second_title: Aspose.Slides para Android a través de la Referencia de API Java
description: Representa opciones de formato de relleno.
type: docs
url: /es/com.aspose.slides/fillformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Representa opciones de formato de relleno.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Devuelve o establece el tipo de relleno. |
| [setFillType(byte value)](#setFillType-byte-) | Devuelve o establece el tipo de relleno. |
| [getSolidFillColor()](#getSolidFillColor--) | Devuelve el color de relleno. |
| [getGradientFormat()](#getGradientFormat--) | Devuelve el formato de relleno de degradado. |
| [getPatternFormat()](#getPatternFormat--) | Devuelve el formato de relleno de patrón. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Devuelve el formato de relleno de imagen. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina si el relleno debe rotarse con la forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina si el relleno debe rotarse con la forma. |
| [getEffective()](#getEffective--) | Obtiene los datos de formato de relleno efectivos con la herencia aplicada. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versión. Solo lectura long.

**Devuelve:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Devuelve o establece el tipo de relleno. Lectura/escritura [FillType](../../com.aspose.slides/filltype).

**Devuelve:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Devuelve o establece el tipo de relleno. Lectura/escritura [FillType](../../com.aspose.slides/filltype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Devuelve el color de relleno. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Devuelve el formato de relleno de degradado. Solo lectura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Devuelve:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Devuelve el formato de relleno de patrón. Solo lectura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Devuelve:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


Devuelve el formato de relleno de imagen. Solo lectura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Devuelve:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Determina si el relleno debe rotarse con la forma. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Determina si el relleno debe rotarse con la forma. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


Obtiene los datos de formato de relleno efectivos con la herencia aplicada.

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


**Devuelve:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Un [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).