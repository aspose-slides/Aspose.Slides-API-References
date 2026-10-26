---
title: Background
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta lo sfondo di una diapositiva.
type: docs
url: /it/com.aspose.slides/background/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Rappresenta lo sfondo di una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Restituisce un tipo di riempimento di sfondo. |
| [setType(byte value)](#setType-byte-) | Restituisce un tipo di riempimento di sfondo. |
| [getFillFormat()](#getFillFormat--) | Restituisce un FillFormat per il riempimento BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Restituisce un EffectFormat per il riempimento BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Restituisce un ColorFormat per un riempimento BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Restituisce un indice del riempimento BackgroundType.Themed nella raccolta dei temi di sfondo. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Restituisce un indice del riempimento BackgroundType.Themed nella raccolta dei temi di sfondo. |
| [getEffective()](#getEffective--) | Ottiene i dati di sfondo effettivi con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Restituisce la diapositiva principale di una forma. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione principale di una diapositiva. |
### getType() {#getType--}
```
public final byte getType()
```


Restituisce un tipo di riempimento di sfondo. Lettura/scrittura [BackgroundType](../../com.aspose.slides/backgroundtype).

**Restituisce:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Restituisce un tipo di riempimento di sfondo. Lettura/scrittura [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Restituisce un FillFormat per il riempimento BackgroundType.OwnBackground. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


Restituisce un EffectFormat per il riempimento BackgroundType.OwnBackground. Solo lettura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Restituisce:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```


Restituisce un ColorFormat per un riempimento BackgroundType.Themed. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```


Restituisce un indice del riempimento BackgroundType.Themed nella raccolta dei temi di sfondo. 0 indica nessun riempimento. 1..999 - indice. Lettura/scrittura int.

**Restituisce:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```


Restituisce un indice del riempimento BackgroundType.Themed nella raccolta dei temi di sfondo. 0 indica nessun riempimento. 1..999 - indice. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```


Ottiene i dati di sfondo effettivi con l'ereditarietà applicata.

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


**Restituisce:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Solo lettura long.

**Restituisce:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```


Restituisce la diapositiva principale di una forma. Solo lettura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Restituisce:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```


Restituisce la presentazione principale di una diapositiva. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[Presentation](../../com.aspose.slides/presentation)