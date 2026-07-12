---
title: BiLevel
second_title: Aspose.Slides Android számára a Java API hivatkozás alapján
description: Kétszintű (fekete/fehér) effektust képvisel.
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

Egy kétszintű (fekete/fehér) effektust képvisel. Azok a bemeneti színek, amelyek luminanciája kisebb a megadott küszöbértéknél, feketére változik. Azok a bemeneti színek, amelyek luminanciája nagyobb vagy egyenlő a megadott értéknél, fehérre lesznek állítva. Az alfa effektus értékeket ez az effektus nem befolyásolja.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony kétszintű effektus adatokat az öröklődés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [BiLevel](../../com.aspose.slides/bilevel) egyenlő-e a jelenlegi [BiLevel](../../com.aspose.slides/bilevel)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Lekéri a hatékony kétszintű effektus adatokat az öröklődés alkalmazásával.

**Visszatér:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [BiLevel](../../com.aspose.slides/bilevel) egyenlő-e a jelenlegi [BiLevel](../../com.aspose.slides/bilevel)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [BiLevel](../../com.aspose.slides/bilevel) a összehasonlításhoz. |

**Visszatér:**
boolean - true, ha az objektumok egyenlőek; egyébként false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatér:**
int - Egy hash kód a jelenlegi objektumhoz.