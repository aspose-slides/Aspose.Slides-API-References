---
title: IBackground
second_title: Aspose.Slides Androidra Java API hivatkozással
description: A dia hátterét képviseli.
type: docs
url: /hu/com.aspose.slides/ibackground/
---
**Az összes megvalósított interfész:** 
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

A dia hátterét képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaad egy háttérkitöltés típusát. |
| [setType(byte value)](#setType-byte-) | Visszaad egy háttérkitöltés típusát. |
| [getFillFormat()](#getFillFormat--) | Visszaad egy FillFormat-ot a BackgroundType.OwnBackground kitöltéshez. |
| [getEffectFormat()](#getEffectFormat--) | Visszaad egy EffectFormat-ot a BackgroundType.OwnBackground kitöltéshez. |
| [getStyleColor()](#getStyleColor--) | Visszaad egy ColorFormat-ot egy BackgroundType.Themed kitöltéshez. |
| [getStyleIndex()](#getStyleIndex--) | Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttértémák gyűjteményében. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttértémák gyűjteményében. |
| [getEffective()](#getEffective--) | Lekéri a hatékony háttéradatokat az öröklődés alkalmazásával. |
### getType() {#getType--}
```
public abstract byte getType()
```


Visszaad egy háttérkitöltés típusát. Olvasás/írás [BackgroundType](../../com.aspose.slides/backgroundtype).

**Visszatérési érték:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Visszaad egy háttérkitöltés típusát. Olvasás/írás [BackgroundType](../../com.aspose.slides/backgroundtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Visszaad egy FillFormat-ot a BackgroundType.OwnBackground kitöltéshez. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatérési érték:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Visszaad egy EffectFormat-ot a BackgroundType.OwnBackground kitöltéshez. Csak olvasható [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatérési érték:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


Visszaad egy ColorFormat-ot egy BackgroundType.Themed kitöltéshez. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttértémák gyűjteményében. 0 jelentése nincs kitöltés. 1..999 - index. Olvasás/írás int.

**Visszatérési érték:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttértémák gyűjteményében. 0 jelentése nincs kitöltés. 1..999 - index. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


Lekéri a hatékony háttéradatokat az öröklődés alkalmazásával.

**Visszatérési érték:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).