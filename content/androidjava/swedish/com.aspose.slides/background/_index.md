---
title: Background
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar bakgrund för en bild.
type: docs
url: /sv/com.aspose.slides/background/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Representerar bakgrund för en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Returnerar en typ av bakgrundsfyllning. |
| [setType(byte value)](#setType-byte-) | Returnerar en typ av bakgrundsfyllning. |
| [getFillFormat()](#getFillFormat--) | Returnerar ett FillFormat för BackgroundType.OwnBackground-fyllning. |
| [getEffectFormat()](#getEffectFormat--) | Returnerar ett EffectFormat för BackgroundType.OwnBackground-fyllning. |
| [getStyleColor()](#getStyleColor--) | Returnerar ett ColorFormat för en BackgroundType.Themed-fyllning. |
| [getStyleIndex()](#getStyleIndex--) | Returnerar ett index för BackgroundType.Themed-fyllning i bakgrundstematssamlingen. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Returnerar ett index för BackgroundType.Themed-fyllning i bakgrundstematssamlingen. |
| [getEffective()](#getEffective--) | Hämtar effektiv bakgrundsdata med ärvning tillämpad. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för en form. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för en bild. |
### getType() {#getType--}
```
public final byte getType()
```

Returnerar en typ av bakgrundsfyllning. Läs/skriv [BackgroundType](../../com.aspose.slides/backgroundtype).

**Returnerar:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Returnerar en typ av bakgrundsfyllning. Läs/skriv [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Returnerar ett FillFormat för BackgroundType.OwnBackground-fyllning. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Returnerar ett EffectFormat för BackgroundType.OwnBackground-fyllning. Skrivskyddad [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returnerar:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Returnerar ett ColorFormat för en BackgroundType.Themed-fyllning. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Returnerar ett index för BackgroundType.Themed-fyllning i bakgrundstematssamlingen. 0 betyder ingen fyllning. 1..999 – index. Läs/skriv int.

**Returnerar:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Returnerar ett index för BackgroundType.Themed-fyllning i bakgrundstematssamlingen. 0 betyder ingen fyllning. 1..999 – index. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Hämtar effektiv bakgrundsdata med ärvning tillämpad.

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

**Returnerar:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Returnerar den överordnade bilden för en form. Skrivskyddad [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returnerar:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Returnerar den överordnade presentationen för en bild. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[Presentation](../../com.aspose.slides/presentation)