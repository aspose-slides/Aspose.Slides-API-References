---
title: IBackground
second_title: Aspose.Slides a Java API Referencia
description: A dia háttérét képviseli.
type: docs
url: /hu/com.aspose.slides/ibackground/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

A dia háttérét képviseli.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaadja a háttér kitöltés típusát. |
| [setType(byte value)](#setType-byte-) | Visszaadja a háttér kitöltés típusát. |
| [getFillFormat()](#getFillFormat--) | Visszaad egy FillFormat-et a BackgroundType.OwnBackground kitöltéshez. |
| [getEffectFormat()](#getEffectFormat--) | Visszaad egy EffectFormat-et a BackgroundType.OwnBackground kitöltéshez. |
| [getStyleColor()](#getStyleColor--) | Visszaad egy ColorFormat-et a BackgroundType.Themed kitöltéshez. |
| [getStyleIndex()](#getStyleIndex--) | Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttér téma gyűjteményben. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttér téma gyűjteményben. |
| [getEffective()](#getEffective--) | Lekéri a hatékony háttér adatokat az öröklődés alkalmazásával. |
### getType() {#getType--}
```
public abstract byte getType()
```

Visszaadja a háttér kitöltés típusát. Olvasás/írás [BackgroundType](../../com.aspose.slides/backgroundtype).

**Visszatér:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Visszaadja a háttér kitöltés típusát. Olvasás/írás [BackgroundType](../../com.aspose.slides/backgroundtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Visszaad egy FillFormat-et a BackgroundType.OwnBackground kitöltéshez. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Visszaad egy EffectFormat-et a BackgroundType.OwnBackground kitöltéshez. Csak olvasható [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatér:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

Visszaad egy ColorFormat-et a BackgroundType.Themed kitöltéshez. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttér téma gyűjteményben. 0 jelentéssel nincs kitöltés. 1..999 - index. Olvasás/írás int.

**Visszatér:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttér téma gyűjteményben. 0 jelentéssel nincs kitöltés. 1..999 - index. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

Lekéri a hatékony háttér adatokat az öröklődés alkalmazásával.

**Visszatér:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).