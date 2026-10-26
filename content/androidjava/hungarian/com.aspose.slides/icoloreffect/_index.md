---
title: IColorEffect
second_title: Aspose.Slides for Android Java API referenciája
description: A színhatást reprezentálja egy animációs viselkedéshez.
type: docs
url: /hu/com.aspose.slides/icoloreffect/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

A színhatást reprezentálja egy animációs viselkedéshez.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getFrom()](#getFrom--) | Ez az érték a viselkedés kezdeti színének meghatározására szolgál. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Ez az érték a viselkedés kezdeti színének meghatározására szolgál. |
| [getTo()](#getTo--) | Leírja a színbeli animáció eredményként kapott színt. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Leírja a színbeli animáció eredményként kapott színt. |
| [getBy()](#getBy--) | Leírja a színanimáció relatív eltolásértékét. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Leírja a színanimáció relatív eltolásértékét. |
| [getColorSpace()](#getColorSpace--) | A viselkedés színtérét képviseli. |
| [setColorSpace(int value)](#setColorSpace-int-) | A viselkedés színtérét képviseli. |
| [getDirection()](#getDirection--) | Meghatározza, hogy a színárnyalat mely irányba körkörözik a színkeréken. |
| [setDirection(int value)](#setDirection-int-) | Meghatározza, hogy a színárnyalat mely irányba körkörözik a színkeréken. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Ez az érték a viselkedés kezdeti színének meghatározására szolgál. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Ez az érték a viselkedés kezdeti színének meghatározására szolgál. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Leírja a színbeli animáció eredményként kapott színt. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Leírja a színbeli animáció eredményként kapott színt. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Leírja a színanimáció relatív eltolásértékét. Olvasás/írás [IColorOffset](../../com.aspose.slides/icoloroffset).

**Visszatérési érték:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Leírja a színanimáció relatív eltolásértékét. Olvasás/írás [IColorOffset](../../com.aspose.slides/icoloroffset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |
### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

A viselkedés színtérét képviseli. Olvasás/írás [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Visszatérési érték:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

A viselkedés színtérét képviseli. Olvasás/írás [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Meghatározza, hogy a színárnyalat mely irányba körkörözik a színkeréken. Olvasás/írás [ColorDirection](../../com.aspose.slides/colordirection).

**Visszatérési érték:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Meghatározza, hogy a színárnyalat mely irányba körkörözik a színkeréken. Olvasás/írás [ColorDirection](../../com.aspose.slides/colordirection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |