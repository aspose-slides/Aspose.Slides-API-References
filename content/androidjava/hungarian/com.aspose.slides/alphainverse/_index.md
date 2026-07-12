---
title: AlphaInverse
second_title: Aspose.Slides for Android a Java API hivatkozásán keresztül
description: Alpha Inverse effektust képvisel.
type: docs
url: /hu/com.aspose.slides/alphainverse/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Alpha Inverse effektust képvisel. Az Alpha (átlátszóság) értékek 100%-ból való kivonással inverzálódnak.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | A hatékony Alpha Inverse effektus adatokat kapja meg, az öröklés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [AlphaInverse](../../com.aspose.slides/alphainverse) egyenlő-e a jelenlegi [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Hash-függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


A hatékony Alpha Inverse effektus adatokat kapja meg, az öröklés alkalmazásával.

**Returns:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - A [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verzió. Csak olvasható long.

**Returns:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott [AlphaInverse](../../com.aspose.slides/alphainverse) egyenlő-e a jelenlegi [AlphaInverse](../../com.aspose.slides/alphainverse).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [AlphaInverse](../../com.aspose.slides/alphainverse) a összehasonlításhoz. |

**Returns:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash-függvényként szolgál egy adott típushoz.

**Returns:**
int - Egy hash kód a jelenlegi objektumhoz.