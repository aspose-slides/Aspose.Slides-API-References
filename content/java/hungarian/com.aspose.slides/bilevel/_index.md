---
title: BiLevel
second_title: Aspose.Slides Java API Referencia
description: Két szintű fekete-fehér effektust képvisel.
type: docs
url: /hu/com.aspose.slides/bilevel/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Két szintű (fekete/fehér) effektet képvisel. A megadott küszöbértéknél kisebb luminanciájú bemeneti színeket feketévé alakítja. A megadott értéknél nagyobb vagy egyenlő luminanciájú bemeneti színeket fehérre állítja. Az alfa effektus értékek nincsenek befolyásolva ezzel az effektussal.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony Bi-Level effekt adatokat az öröklés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [BiLevel](../../com.aspose.slides/bilevel) egyenlő-e a jelenlegi [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Lekéri a hatékony Bi-Level effekt adatokat az öröklés alkalmazásával.

**Visszatérési érték:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [BiLevel](../../com.aspose.slides/bilevel) egyenlő-e a jelenlegi [BiLevel](../../com.aspose.slides/bilevel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [BiLevel](../../com.aspose.slides/bilevel) a összehasonlításhoz. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Egy hash kód a jelenlegi objektumhoz.