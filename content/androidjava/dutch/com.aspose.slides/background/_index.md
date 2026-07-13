---
title: Background
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de achtergrond van een dia voor.
type: docs
url: /nl/com.aspose.slides/background/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Stelt de achtergrond van een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Retourneert een type achtergrondvulling. |
| [setType(byte value)](#setType-byte-) | Retourneert een type achtergrondvulling. |
| [getFillFormat()](#getFillFormat--) | Retourneert een FillFormat voor de BackgroundType.OwnBackground vulling. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert een EffectFormat voor de BackgroundType.OwnBackground vulling. |
| [getStyleColor()](#getStyleColor--) | Retourneert een ColorFormat voor een BackgroundType.Themed vulling. |
| [getStyleIndex()](#getStyleIndex--) | Retourneert een index van de BackgroundType.Themed vulling in de achtergrondthema-collectie. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Retourneert een index van de BackgroundType.Themed vulling in de achtergrondthema-collectie. |
| [getEffective()](#getEffective--) | Haalt de effectieve achtergrondgegevens op met de toepaste erfenis. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een vorm. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een dia. |
### getType() {#getType--}
```
public final byte getType()
```


Retourneert een type achtergrondvulling. Lezen/Schrijven [BackgroundType](../../com.aspose.slides/backgroundtype).

**Retour:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Retourneert een type achtergrondvulling. Lezen/Schrijven [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Retourneert een FillFormat voor de BackgroundType.OwnBackground vulling. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


Retourneert een EffectFormat voor de BackgroundType.OwnBackground vulling. Alleen-lezen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retour:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```


Retourneert een ColorFormat voor een BackgroundType.Themed vulling. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```


Retourneert een index van de BackgroundType.Themed vulling in de achtergrondthema-collectie. 0 betekent geen vulling. 1..999 - index. Lezen/Schrijven int.

**Retour:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```


Retourneert een index van de BackgroundType.Themed vulling in de achtergrondthema-collectie. 0 betekent geen vulling. 1..999 - index. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```


Haalt de effectieve achtergrondgegevens op met de toepaste erfenis.

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

**Retour:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```


Retourneert de bovenliggende dia van een vorm. Alleen-lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retour:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```


Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retour:**
[Presentation](../../com.aspose.slides/presentation)