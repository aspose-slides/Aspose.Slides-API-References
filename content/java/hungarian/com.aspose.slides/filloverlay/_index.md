---
title: FillOverlay
second_title: Aspose.Slides Java API hivatkozás
description: Egy Fill Overlay effektust képvisel.
type: docs
url: /hu/com.aspose.slides/filloverlay/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Egy Fill Overlay effektust képvisel. A Fill Overlay használható egy további kitöltés megadására egy objektumhoz, és a két kitöltést összekeverve.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Kitöltési formátum. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Megkapja a hatékony Fill Overlay effektus adatokat az öröklődés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [FillOverlay](../../com.aspose.slides/filloverlay) egyenlő-e a jelenlegi [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Kitöltési formátum. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatérési érték:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. Olvasás/írás [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Visszatérési érték:**
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Olvasás/írás [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Megkapja a hatékony Fill Overlay effektus adatokat az öröklődés alkalmazásával.

**Visszatérési érték:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatérési érték:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [FillOverlay](../../com.aspose.slides/filloverlay) egyenlő-e a jelenlegi [FillOverlay](../../com.aspose.slides/filloverlay).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [FillOverlay](../../com.aspose.slides/filloverlay) az összehasonlítandó. |

**Visszatérési érték:**
boolean - true, ha az objektumok egyenlőek; egyébként false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - A hash kód az aktuális objektumhoz.