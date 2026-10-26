---
title: AlphaInverse
second_title: Aspose.Slides Java API referencia
description: Az Alpha Inverse effektet reprezentálja.
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

Az Alpha Inverse effektet képviseli. Az alfa (átlátszóság) értékeket 100%-ból kivonással invertálják.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Inverse effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaInverse](../../com.aspose.slides/alphainverse) is equal to the current [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Az öröklés alkalmazásával lekéri a hatékony Alpha Inverse effekt adatokat.

**Visszatérési érték:**  
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) – Egy [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
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

Meghatározza, hogy a megadott [AlphaInverse](../../com.aspose.slides/alphainverse) egyenlő-e a jelenlegi [AlphaInverse](../../com.aspose.slides/alphainverse)-val.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [AlphaInverse](../../com.aspose.slides/alphainverse) az összehasonlításhoz. |

**Visszatérési érték:**  
boolean – igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash-függvényként szolgál egy adott típushoz.

**Visszatérési érték:**  
int – Egy hash-kód a jelenlegi objektumhoz.