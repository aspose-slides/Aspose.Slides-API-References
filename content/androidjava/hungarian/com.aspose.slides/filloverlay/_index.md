---
title: FillOverlay
second_title: Aspose.Slides Androidhoz a Java API referencia szerint
description: Egy Fill Overlay effektust képvisel.
type: docs
url: /hu/com.aspose.slides/filloverlay/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Egy Fill Overlay effektust képvisel. A fill overlay használható egy objektum további kitöltésének meghatározására, és a két kitöltés összekeverésére.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Kitöltési formátum. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Lekéri a hatékony Fill Overlay effektus adatait az öröklődés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [FillOverlay](../../com.aspose.slides/filloverlay) egyenlő-e a jelenlegi [FillOverlay](../../com.aspose.slides/filloverlay)-val. |
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

FillBlendMode. Olvasható/írható [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Visszatérési érték:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Olvasható/írható [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Lekéri a hatékony Fill Overlay effektus adatait az öröklődés alkalmazásával.

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

Megállapítja, hogy a megadott [FillOverlay](../../com.aspose.slides/filloverlay) egyenlő-e a jelenlegi [FillOverlay](../../com.aspose.slides/filloverlay)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [FillOverlay](../../com.aspose.slides/filloverlay) a összehasonlításhoz. |

**Visszatérési érték:**
boolean - true, ha az objektumok egyenlőek; egyébként false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Egy hash kód a jelenlegi objektumhoz.