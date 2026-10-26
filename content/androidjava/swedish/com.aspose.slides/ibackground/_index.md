---
title: IBackground
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar bakgrunden på en bild.
type: docs
url: /sv/com.aspose.slides/ibackground/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Representerar bakgrunden på en bild.
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
| [getEffective()](#getEffective--) | Hämtar effektiv bakgrundsdata med ärftlighet tillämpad. |
### getType() {#getType--}
```
public abstract byte getType()
```


Returnerar en typ av bakgrundsfyllning. Läs/skriv [BackgroundType](../../com.aspose.slides/backgroundtype).

**Returnerar:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Returnerar en typ av bakgrundsfyllning. Läs/skriv [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Returnerar ett FillFormat för BackgroundType.OwnBackground-fyllning. Endast läsning [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Returnerar ett EffectFormat för BackgroundType.OwnBackground-fyllning. Endast läsning [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returnerar:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


Returnerar ett ColorFormat för en BackgroundType.Themed-fyllning. Endast läsning [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


Returnerar ett index för BackgroundType.Themed-fyllning i bakgrundstematssamlingen. 0 betyder ingen fyllning. 1..999 - index. Läs/skriv int.

**Returnerar:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


Returnerar ett index för BackgroundType.Themed-fyllning i bakgrundstematssamlingen. 0 betyder ingen fyllning. 1..999 - index. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


Hämtar effektiv bakgrundsdata med ärftlighet tillämpad.

**Returnerar:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - En [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).