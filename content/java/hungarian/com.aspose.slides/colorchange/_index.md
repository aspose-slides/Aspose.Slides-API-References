---
title: ColorChange
second_title: Aspose.Slides for Java API Referencia
description: Egy Color Change effektust képvisel.
type: docs
url: /hu/com.aspose.slides/colorchange/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

A Color Change effektust képviseli. A FromColor példányait a ToColor példányai cserélik le.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFromColor()](#getFromColor--) | A helyettesítendő szín. |
| [getToColor()](#getToColor--) | A helyettesítő szín. |
| [getEffective()](#getEffective--) | Az öröklődés alkalmazásával hatékony Color Change effektus adatot adja vissza. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [ColorChange](../../com.aspose.slides/colorchange) egyenlő-e a jelenlegi [ColorChange](../../com.aspose.slides/colorchange)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

A helyettesítendő szín. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

A helyettesítő szín. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Az öröklődés alkalmazásával hatékony Color Change effektus adatot adja vissza.

**Visszatérési érték:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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

Megállapítja, hogy a megadott [ColorChange](../../com.aspose.slides/colorchange) egyenlő-e a jelenlegi [ColorChange](../../com.aspose.slides/colorchange)-rel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [ColorChange](../../com.aspose.slides/colorchange) a összehasonlításhoz. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Az aktuális objektum hash kódja.