---
title: IColorEffect
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Farbeffekt für ein Animationsverhalten dar.
type: docs
url: /de/com.aspose.slides/icoloreffect/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Stellt einen Farbeffekt für ein Animationsverhalten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFrom()](#getFrom--) | Dieser Wert wird verwendet, um die Ausgangsfarbe des Verhaltens festzulegen. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Dieser Wert wird verwendet, um die Ausgangsfarbe des Verhaltens festzulegen. |
| [getTo()](#getTo--) | Beschreibt die resultierende Farbe für die Farbänderung der Animation. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Beschreibt die resultierende Farbe für die Farbänderung der Animation. |
| [getBy()](#getBy--) | Beschreibt den relativen Offsetwert für die Farbanimation. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Beschreibt den relativen Offsetwert für die Farbanimation. |
| [getColorSpace()](#getColorSpace--) | Stellt den Farbraum des Verhaltens dar. |
| [setColorSpace(int value)](#setColorSpace-int-) | Stellt den Farbraum des Verhaltens dar. |
| [getDirection()](#getDirection--) | Gibt an, in welche Richtung der Farbton im Farbkreis gedreht wird. |
| [setDirection(int value)](#setDirection-int-) | Gibt an, in welche Richtung der Farbton im Farbkreis gedreht wird. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```


Dieser Wert wird verwendet, um die Ausgangsfarbe des Verhaltens festzulegen. Lesen/Schreiben [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```


Dieser Wert wird verwendet, um die Ausgangsfarbe des Verhaltens festzulegen. Lesen/Schreiben [IColorFormat](../../com.aspose.slides/icolorformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```


Beschreibt die resultierende Farbe für die Farbänderung der Animation. Lesen/Schreiben [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```


Beschreibt die resultierende Farbe für die Farbänderung der Animation. Lesen/Schreiben [IColorFormat](../../com.aspose.slides/icolorformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```


Beschreibt den relativen Offsetwert für die Farbanimation. Lesen/Schreiben [IColorOffset](../../com.aspose.slides/icoloroffset).

**Rückgabewert:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```


Beschreibt den relativen Offsetwert für die Farbanimation. Lesen/Schreiben [IColorOffset](../../com.aspose.slides/icoloroffset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```


Stellt den Farbraum des Verhaltens dar. Lesen/Schreiben [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Rückgabewert:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```


Stellt den Farbraum des Verhaltens dar. Lesen/Schreiben [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Gibt an, in welche Richtung der Farbton im Farbkreis gedreht wird. Lesen/Schreiben [ColorDirection](../../com.aspose.slides/colordirection).

**Rückgabewert:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Gibt an, in welche Richtung der Farbton im Farbkreis gedreht wird. Lesen/Schreiben [ColorDirection](../../com.aspose.slides/colordirection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |