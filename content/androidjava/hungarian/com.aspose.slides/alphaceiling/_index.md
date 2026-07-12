---
title: AlphaCeiling
second_title: Aspose.Slides Androidra a Java API hivatkozáson keresztül
description: Alpha Ceiling effektet képvisel.
type: docs
url: /hu/com.aspose.slides/alphaceiling/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

Egy Alpha Ceiling effektet képvisel. A nulla feletti Alpha (átlátszóság) értékek 100%-ra módosulnak. Más szóval, minden részben áttetsző teljesen áttetszővé válik.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony Alpha Ceiling effekt adatait az öröklés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [AlphaCeiling](../../com.aspose.slides/alphaceiling) egyenlő-e a jelenlegi [AlphaCeiling](../../com.aspose.slides/alphaceiling)-vel. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```

Lekéri a hatékony Alpha Ceiling effekt adatait az öröklés alkalmazásával.

**Visszatérési érték:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - egy [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [AlphaCeiling](../../com.aspose.slides/alphaceiling) egyenlő-e a jelenlegi [AlphaCeiling](../../com.aspose.slides/alphaceiling)-vel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [AlphaCeiling](../../com.aspose.slides/alphaceiling) az összehasonlításhoz. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - A jelenlegi objektum hash kódja.