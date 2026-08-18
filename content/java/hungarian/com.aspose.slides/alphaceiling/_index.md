---
title: AlphaCeiling
second_title: Aspose.Slides Java API hivatkozás
description: Alpha Ceiling effektust reprezentál.
type: docs
url: /hu/com.aspose.slides/alphaceiling/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden Megvalósított Interfész:**
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

Alpha Ceiling effektust reprezentálja. A nulla-nál nagyobb Alpha (átlátszatlanság) értékek 100%-ra változnak. Más szóval, minden részben átlátszatlan teljesen átlátszatlanná válik.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony Alpha Ceiling effekt adatot az öröklődés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [AlphaCeiling](../../com.aspose.slides/alphaceiling) egyenlő-e a jelenlegi [AlphaCeiling](../../com.aspose.slides/alphaceiling). |
| [hashCode()](#hashCode--) | Hasítógenerátorként szolgál egy adott típus számára. |
### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```


Lekéri a hatékony Alpha Ceiling effekt adatot az öröklődés alkalmazásával.

**Visszatérési érték:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - Egy [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott [AlphaCeiling](../../com.aspose.slides/alphaceiling) egyenlő-e a jelenlegi [AlphaCeiling](../../com.aspose.slides/alphaceiling).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [AlphaCeiling](../../com.aspose.slides/alphaceiling) a összehasonlításhoz. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hasítógenerátorként szolgál egy adott típus számára.

**Visszatérési érték:**
int - Az aktuális objektum hash kódja.