---
title: IColorEffect
second_title: Aspose.Slides Java API referenciája
description: Egy animációs viselkedés színhatását reprezentálja.
type: docs
url: /hu/com.aspose.slides/icoloreffect/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Egy animációs viselkedés színhatását reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFrom()](#getFrom--) | Ez az érték a viselkedés kezdőszínének meghatározására szolgál. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Ez az érték a viselkedés kezdőszínének meghatározására szolgál. |
| [getTo()](#getTo--) | Leírja az animáció színváltozásának eredményül kapott színét. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Leírja az animáció színváltozásának eredményül kapott színét. |
| [getBy()](#getBy--) | Leírja a színanimáció relatív eltolási értékét. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Leírja a színanimáció relatív eltolási értékét. |
| [getColorSpace()](#getColorSpace--) | A viselkedés színtérét reprezentálja. |
| [setColorSpace(int value)](#setColorSpace-int-) | A viselkedés színtérét reprezentálja. |
| [getDirection()](#getDirection--) | Megadja, hogy melyik irányban kell körbeforgatni a színt a színkörön. |
| [setDirection(int value)](#setDirection-int-) | Megadja, hogy melyik irányban kell körbeforgatni a színt a színkörön. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Ez az érték a viselkedés kezdőszínének meghatározására szolgál. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Ez az érték a viselkedés kezdőszínének meghatározására szolgál. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Leírja az animáció színváltozásának eredményül kapott színét. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Leírja az animáció színváltozásának eredményül kapott színét. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Leírja a színanimáció relatív eltolási értékét. Olvasás/írás [IColorOffset](../../com.aspose.slides/icoloroffset).

**Visszatérési érték:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Leírja a színanimáció relatív eltolási értékét. Olvasás/írás [IColorOffset](../../com.aspose.slides/icoloroffset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

A viselkedés színtérét reprezentálja. Olvasás/írás [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Visszatérési érték:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

A viselkedés színtérét reprezentálja. Olvasás/írás [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Megadja, hogy melyik irányban kell körbeforgatni a színt a színkörön. Olvasás/írás [ColorDirection](../../com.aspose.slides/colordirection).

**Visszatérési érték:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Megadja, hogy melyik irányban kell körbeforgatni a színt a színkörön. Olvasás/írás [ColorDirection](../../com.aspose.slides/colordirection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |