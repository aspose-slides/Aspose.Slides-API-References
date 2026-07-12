---
title: Duotone
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: Duotone hatást képvisel.
type: docs
url: /hu/com.aspose.slides/duotone/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Duotone hatást képvisel. Minden képpont esetén lineáris interpolációval kombinálja a Color1 és Color2 értékeket, hogy meghatározza az új színt a képpont számára.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getColor1()](#getColor1--) | Visszaadja a cél színformátumot sötét képpontokhoz. |
| [getColor2()](#getColor2--) | Visszaadja a cél színformátumot világos képpontokhoz. |
| [getEffective()](#getEffective--) | Lekéri a hatékony Duotone effektus adatokat az öröklődés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a megadott [Duotone](../../com.aspose.slides/duotone) egyenlő-e az aktuális [Duotone](../../com.aspose.slides/duotone)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Visszaadja a cél színformátumot sötét képpontokhoz. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Visszaadja a cél színformátumot világos képpontokhoz. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Lekéri a hatékony Duotone effektus adatokat az öröklődés alkalmazásával.

**Visszatér:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
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


Megállapítja, hogy a megadott [Duotone](../../com.aspose.slides/duotone) egyenlő-e az aktuális [Duotone](../../com.aspose.slides/duotone)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [Duotone](../../com.aspose.slides/duotone) a összehasonlításhoz. |

**Visszatér:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatér:**
int - Egy hash kód a jelenlegi objektumhoz.