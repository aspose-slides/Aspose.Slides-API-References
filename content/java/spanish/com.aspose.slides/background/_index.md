---
title: Background
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa el fondo de una diapositiva.
type: docs
url: /es/com.aspose.slides/background/
---
**Herencia:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**  
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject  
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Representa el fondo de una diapositiva.

## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Retorna un tipo de relleno de fondo. |
| [setType(byte value)](#setType-byte-) | Retorna un tipo de relleno de fondo. |
| [getFillFormat()](#getFillFormat--) | Retorna un FillFormat para el relleno BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Retorna un EffectFormat para el relleno BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Retorna un ColorFormat para un relleno BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Retorna un índice del relleno BackgroundType.Themed en la colección de temas de fondo. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Retorna un índice del relleno BackgroundType.Themed en la colección de temas de fondo. |
| [getEffective()](#getEffective--) | Obtiene los datos de fondo efectivos con la herencia aplicada. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Retorna la diapositiva padre de una forma. |
| [getPresentation()](#getPresentation--) | Retorna la presentación padre de una diapositiva. |

### getType() {#getType--}
```
public final byte getType()
```

Retorna un tipo de relleno de fondo. Lectura/escritura [BackgroundType](../../com.aspose.slides/backgroundtype).

**Devuelve:**  
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Retorna un tipo de relleno de fondo. Lectura/escritura [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Retorna un FillFormat para el relleno BackgroundType.OwnBackground. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Retorna un EffectFormat para el relleno BackgroundType.OwnBackground. Solo lectura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Devuelve:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Retorna un ColorFormat para un relleno BackgroundType.Themed. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Retorna un índice del relleno BackgroundType.Themed en la colección de temas de fondo. 0 significa sin relleno. 1..999 - índice. Lectura/escritura int.

**Devuelve:**  
int

### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Retorna un índice del relleno BackgroundType.Themed en la colección de temas de fondo. 0 significa sin relleno. 1..999 - índice. Lectura/escritura int.

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
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).

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

Retorna el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**  
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Retorna la diapositiva padre de una forma. Solo lectura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Devuelve:**  
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Retorna la presentación padre de una diapositiva. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**  
[Presentation](../../com.aspose.slides/presentation)