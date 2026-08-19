---
title: IBackground
second_title: Aspose.Slides voor Java API Referentie
description: Stelt de achtergrond van een dia voor.
type: docs
url: /nl/com.aspose.slides/ibackground/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Stelt de achtergrond van een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Retourneert een type achtergrondvulling. |
| [setType(byte value)](#setType-byte-) | Retourneert een type achtergrondvulling. |
| [getFillFormat()](#getFillFormat--) | Retourneert een FillFormat voor BackgroundType.OwnBackground vulling. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert een EffectFormat voor BackgroundType.OwnBackground vulling. |
| [getStyleColor()](#getStyleColor--) | Retourneert een ColorFormat voor een BackgroundType.Themed vulling. |
| [getStyleIndex()](#getStyleIndex--) | Retourneert een index van BackgroundType.Themed vulling in de achtergrondthemacollectie. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Retourneert een index van BackgroundType.Themed vulling in de achtergrondthemacollectie. |
| [getEffective()](#getEffective--) | Haalt effectieve achtergrondgegevens op met de overerving toegepast. |
### getType() {#getType--}
```
public abstract byte getType()
```


Retourneert een type achtergrondvulling. Lezen/Schrijven [BackgroundType](../../com.aspose.slides/backgroundtype).

**Retour:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Retourneert een type achtergrondvulling. Lezen/Schrijven [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Retourneert een FillFormat voor BackgroundType.OwnBackground vulling. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Retourneert een EffectFormat voor BackgroundType.OwnBackground vulling. Alleen-lezen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retour:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


Retourneert een ColorFormat voor een BackgroundType.Themed vulling. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


Retourneert een index van BackgroundType.Themed vulling in de achtergrondthemacollectie. 0 betekent geen vulling. 1..999 - index. Lezen/Schrijven int.

**Retour:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


Retourneert een index van BackgroundType.Themed vulling in de achtergrondthemacollectie. 0 betekent geen vulling. 1..999 - index. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


Haalt de effectieve achtergrondgegevens op met de overerving toegepast.

**Retour:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).