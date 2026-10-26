---
title: Background
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa el fondo de una diapositiva.
type: docs
url: /es/com.aspose.slides/background/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Representa el fondo de una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Devuelve un tipo de relleno de fondo. |
| [setType(byte value)](#setType-byte-) | Devuelve un tipo de relleno de fondo. |
| [getFillFormat()](#getFillFormat--) | Devuelve un FillFormat para el relleno BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Devuelve un EffectFormat para el relleno BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Devuelve un ColorFormat para un relleno BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Devuelve un índice del relleno BackgroundType.Themed en la colección de temas de fondo. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Devuelve un índice del relleno BackgroundType.Themed en la colección de temas de fondo. |
| [getEffective()](#getEffective--) | Obtiene los datos de fondo efectivos con la herencia aplicada. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Devuelve la diapositiva principal de una forma. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación principal de una diapositiva. |
### getType() {#getType--}
```
public final byte getType()
```


Devuelve un tipo de relleno de fondo. Lectura/escritura [BackgroundType](../../com.aspose.slides/backgroundtype).

**Devuelve:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Devuelve un tipo de relleno de fondo. Lectura/escritura [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Devuelve un FillFormat para el relleno BackgroundType.OwnBackground. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


Devuelve un EffectFormat para el relleno BackgroundType.OwnBackground. Solo lectura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Devuelve:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```


Devuelve un ColorFormat para un relleno BackgroundType.Themed. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```


Devuelve un índice del relleno BackgroundType.Themed en la colección de temas de fondo. 0 significa sin relleno. 1..999 - índice. Lectura/escritura int.

**Devuelve:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```


Devuelve un índice del relleno BackgroundType.Themed en la colección de temas de fondo. 0 significa sin relleno. 1..999 - índice. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```


Obtiene los datos de fondo efectivos con la herencia aplicada.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - Un [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versión. Solo lectura long.

**Devuelve:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```


Devuelve la diapositiva principal de una forma. Solo lectura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Devuelve:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```


Devuelve la presentación principal de una diapositiva. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[Presentation](../../com.aspose.slides/presentation)