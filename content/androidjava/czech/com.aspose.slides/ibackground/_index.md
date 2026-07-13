---
title: IBackground
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje pozadí snímku.
type: docs
url: /cs/com.aspose.slides/ibackground/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Represents background of a slide.
## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Vrací typ výplně pozadí. |
| [setType(byte value)](#setType-byte-) | Vrací typ výplně pozadí. |
| [getFillFormat()](#getFillFormat--) | Vrací FillFormat pro výplň BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Vrací EffectFormat pro výplň BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Vrací ColorFormat pro výplň BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Vrací index výplně BackgroundType.Themed ve sbírce témat pozadí. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Vrací index výplně BackgroundType.Themed ve sbírce témat pozadí. |
| [getEffective()](#getEffective--) | Získá efektivní data pozadí s aplikovaným děděním. |
### getType() {#getType--}
```
public abstract byte getType()
```


Vrací typ výplně pozadí. Čtení/Zápis [BackgroundType](../../com.aspose.slides/backgroundtype).

**Vrací:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Vrací typ výplně pozadí. Čtení/Zápis [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Vrací FillFormat pro výplň BackgroundType.OwnBackground. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Vrací EffectFormat pro výplň BackgroundType.OwnBackground. Pouze pro čtení [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Vrací:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


Vrací ColorFormat pro výplň BackgroundType.Themed. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


Vrací index výplně BackgroundType.Themed ve sbírce témat pozadí. 0 znamená žádnou výplň. 1..999 - index. Čtení/Zápis int.

**Vrací:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


Vrací index výplně BackgroundType.Themed ve sbírce témat pozadí. 0 znamená žádnou výplň. 1..999 - index. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


Získá efektivní data pozadí s aplikovaným děděním.

**Vrací:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).