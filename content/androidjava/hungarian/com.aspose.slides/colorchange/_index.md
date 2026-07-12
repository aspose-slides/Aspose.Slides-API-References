---
title: ColorChange
second_title: Aspose.Slides Android számára a Java API referencia
description: Egy színváltoztatási hatást reprezentál.
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

A Color Change effektust reprezentálja. A FromColor példányait a ToColor példányai helyettesítik.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getFromColor()](#getFromColor--) | A szín, amely helyettesítve lesz. |
| [getToColor()](#getToColor--) | A szín, amely helyettesíti. |
| [getEffective()](#getEffective--) | Lekéri a hatékony Color Change effektus adatokat az öröklés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [ColorChange](../../com.aspose.slides/colorchange) egyenlő-e a jelenlegi [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Hash-funkcióként szolgál egy adott típushoz. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

A szín, amely helyettesítve lesz. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

A szín, amely helyettesíti. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Lekéri a hatékony Color Change effektus adatokat az öröklés alkalmazásával.

**Visszatér:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [ColorChange](../../com.aspose.slides/colorchange) egyenlő-e a jelenlegi [ColorChange](../../com.aspose.slides/colorchange).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [ColorChange](../../com.aspose.slides/colorchange) az összehasonlításhoz. |

**Visszatér:**
boolean - true, ha az objektumok egyenlőek; egyébként false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash-funkcióként szolgál egy adott típushoz.

**Visszatér:**
int - A hashkód a jelenlegi objektumhoz.