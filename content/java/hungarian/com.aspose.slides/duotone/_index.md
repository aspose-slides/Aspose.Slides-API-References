---
title: Duotone
second_title: Aspose.Slides Java API referencia
description: Duotone hatást reprezentál.
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

Duotone hatást reprezentál. Minden pixel esetén a Color1 és Color2 lineáris interpolációval kombinálásával határozza meg az új színt a pixelhez.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getColor1()](#getColor1--) | Visszaadja a sötét pixelek cél színformátumát. |
| [getColor2()](#getColor2--) | Visszaadja a világos pixelek cél színformátumát. |
| [getEffective()](#getEffective--) | Lekéri a hatékony Duotone effektus adatokat az öröklődés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a megadott [Duotone](../../com.aspose.slides/duotone) egyenlő-e a jelenlegi [Duotone](../../com.aspose.slides/duotone)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típus számára. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

Visszaadja a sötét pixelek cél színformátumát. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

Visszaadja a világos pixelek cél színformátumát. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

Lekéri a hatékony Duotone effektus adatokat az öröklődés alkalmazásával.

**Visszatérési érték:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - Egy [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
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

Meghatározza, hogy a megadott [Duotone](../../com.aspose.slides/duotone) egyenlő-e a jelenlegi [Duotone](../../com.aspose.slides/duotone)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [Duotone](../../com.aspose.slides/duotone) az összehasonlításhoz. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típus számára.

**Visszatérési érték:**
int - Az aktuális objektum hash kódja.