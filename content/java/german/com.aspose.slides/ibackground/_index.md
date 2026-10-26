---
title: IBackground
second_title: Aspose.Slides für Java API-Referenz
description: Stellt den Hintergrund einer Folie dar.
type: docs
url: /de/com.aspose.slides/ibackground/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Stellt den Hintergrund einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt einen Typ der Hintergrundfüllung zurück. |
| [setType(byte value)](#setType-byte-) | Gibt einen Typ der Hintergrundfüllung zurück. |
| [getFillFormat()](#getFillFormat--) | Gibt ein FillFormat für die Fill von BackgroundType.OwnBackground zurück. |
| [getEffectFormat()](#getEffectFormat--) | Gibt ein EffectFormat für die Fill von BackgroundType.OwnBackground zurück. |
| [getStyleColor()](#getStyleColor--) | Gibt ein ColorFormat für eine BackgroundType.Themed-Füllung zurück. |
| [getStyleIndex()](#getStyleIndex--) | Gibt einen Index der BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Gibt einen Index der BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. |
| [getEffective()](#getEffective--) | Erhält effektive Hintergrunddaten mit angewandter Vererbung. |
### getType() {#getType--}
```
public abstract byte getType()
```

Gibt einen Typ der Hintergrundfüllung zurück. Lesen/Schreiben [BackgroundType](../../com.aspose.slides/backgroundtype).

**Rückgabewert:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Gibt einen Typ der Hintergrundfüllung zurück. Lesen/Schreiben [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Gibt ein FillFormat für die Fill von BackgroundType.OwnBackground zurück. Nur-Lesen [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabewert:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Gibt ein EffectFormat für die Fill von BackgroundType.OwnBackground zurück. Nur-Lesen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Rückgabewert:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

Gibt ein ColorFormat für eine BackgroundType.Themed-Füllung zurück. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

Gibt einen Index der BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. 0 bedeutet keine Füllung. 1..999 – Index. Lesen/Schreiben int.

**Rückgabewert:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

Gibt einen Index der BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. 0 bedeutet keine Füllung. 1..999 – Index. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

Erhält effektive Hintergrunddaten mit angewandter Vererbung.

**Rückgabewert:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - Ein [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).