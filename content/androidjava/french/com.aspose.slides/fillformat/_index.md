---
title: FillFormat
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente des options de mise en forme de remplissage.
type: docs
url: /fr/com.aspose.slides/fillformat/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Représente les options de mise en forme du remplissage.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Renvoie ou définit le type de remplissage. |
| [setFillType(byte value)](#setFillType-byte-) | Renvoie ou définit le type de remplissage. |
| [getSolidFillColor()](#getSolidFillColor--) | Renvoie la couleur du remplissage. |
| [getGradientFormat()](#getGradientFormat--) | Renvoie le format de remplissage en dégradé. |
| [getPatternFormat()](#getPatternFormat--) | Renvoie le format de remplissage en motif. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Renvoie le format de remplissage d'image. |
| [getRotateWithShape()](#getRotateWithShape--) | Détermine si le remplissage doit être tourné avec la forme. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Détermine si le remplissage doit être tourné avec la forme. |
| [getEffective()](#getEffective--) | Obtient les données de mise en forme de remplissage effectives avec l'héritage appliqué. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Renvoie ou définit le type de remplissage. Lecture/écriture [FillType](../../com.aspose.slides/filltype).

**Renvoie :**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Renvoie ou définit le type de remplissage. Lecture/écriture [FillType](../../com.aspose.slides/filltype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Renvoie la couleur du remplissage. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Renvoie le format de remplissage en dégradé. Lecture seule [IGradientFormat](../../com.aspose.slides/igradientformat).

**Renvoie :**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Renvoie le format de remplissage en motif. Lecture seule [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Renvoie :**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

Renvoie le format de remplissage d'image. Lecture seule [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Renvoie :**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Détermine si le remplissage doit être tourné avec la forme. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Détermine si le remplissage doit être tourné avec la forme. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

Obtient les données de mise en forme de remplissage effectives avec l'héritage appliqué.

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

**Renvoie :**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Un [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).