---
title: AlphaBiLevel
second_title: Aspose.Slides Androidhoz a Java API hivatkozásban
description: Alpha Bi-Level effektust reprezentál.
type: docs
url: /hu/com.aspose.slides/alphabilevel/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Alpha Bi-Level effektust reprezentál. Az Alpha (Átlátszatlanság) értékek, amelyek kisebbek a küszöbértéknél, 0-ra (teljesen átlátszó) változnak, és az alpha értékek, amelyek nagyobbak vagy egyenlőek a küszöbértékkel, 100%-ra (teljesen átlátszatlan) változnak.
## Methods

| Módszer | Leírás |
| --- | --- |
| [getThreshold()](#getThreshold--) | Visszaadja a hatás küszöbértékét. |
| [setThreshold(float value)](#setThreshold-float-) | Visszaadja a hatás küszöbértékét. |
| [getEffective()](#getEffective--) | Megkapja a hatékony Alpha Bi-Level effektus adatokat az öröklődés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [AlphaBiLevel](../../com.aspose.slides/alphabilevel) egyenlő-e a jelenlegi [AlphaBiLevel](../../com.aspose.slides/alphabilevel)-vel. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Visszaadja a hatás küszöbértékét. Olvasás/írás float.

**Visszatérési érték:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Visszaadja a hatás küszöbértékét. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Megkapja a hatékony Alpha Bi-Level effektus adatokat az öröklődés alkalmazásával.

**Visszatérési érték:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - Egy [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [AlphaBiLevel](../../com.aspose.slides/alphabilevel) egyenlő-e a jelenlegi [AlphaBiLevel](../../com.aspose.slides/alphabilevel)-vel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [AlphaBiLevel](../../com.aspose.slides/alphabilevel) a összehasonlításhoz. |

**Visszatérési érték:**
boolean - true ha az objektumok egyenlőek; egyébként false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Egy hash kód a jelenlegi objektumhoz.