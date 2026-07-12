---
title: FillFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções de formatação de preenchimento.
type: docs
url: /pt/com.aspose.slides/fillformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Representa opções de formatação de preenchimento.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Retorna ou define o tipo de preenchimento. |
| [setFillType(byte value)](#setFillType-byte-) | Retorna ou define o tipo de preenchimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Retorna a cor de preenchimento. |
| [getGradientFormat()](#getGradientFormat--) | Retorna o formato de preenchimento gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Retorna o formato de preenchimento de padrão. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Retorna o formato de preenchimento de imagem. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se o preenchimento deve ser girado com a forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina se o preenchimento deve ser girado com a forma. |
| [getEffective()](#getEffective--) | Obtém dados de formatação de preenchimento efetivos com a herança aplicada. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versão. Somente leitura long.

**Retorna:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Retorna ou define o tipo de preenchimento. Leitura/gravação [FillType](../../com.aspose.slides/filltype).

**Retorna:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Retorna ou define o tipo de preenchimento. Leitura/gravação [FillType](../../com.aspose.slides/filltype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Retorna a cor de preenchimento. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Retorna o formato de preenchimento gradiente. Somente leitura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Retorna:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Retorna o formato de preenchimento de padrão. Somente leitura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Retorna:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


Retorna o formato de preenchimento de imagem. Somente leitura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retorna:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Determina se o preenchimento deve ser girado com a forma. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Determina se o preenchimento deve ser girado com a forma. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


Obtém dados de formatação de preenchimento efetivos com a herança aplicada.

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

**Retorna:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Um [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).