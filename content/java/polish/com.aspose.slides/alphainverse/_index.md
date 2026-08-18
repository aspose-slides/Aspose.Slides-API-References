---
title: AlphaInverse
second_title: Aspose.Slides dla referencji API Java
description: Reprezentuje efekt Alpha Inverse.
type: docs
url: /pl/com.aspose.slides/alphainverse/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Reprezentuje efekt Alpha Inverse. Wartości Alpha (przezroczystość) są odwracane poprzez odjęcie od 100%.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane efektu Alpha Inverse z zastosowanym dziedziczeniem. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy określony [AlphaInverse](../../com.aspose.slides/alphainverse) jest równy bieżącemu [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Działa jako funkcja skrótu dla określonego typu. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


Pobiera skuteczne dane efektu Alpha Inverse z zastosowanym dziedziczeniem.

**Zwraca:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - A [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu long.

**Zwraca:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Określa, czy określony [AlphaInverse](../../com.aspose.slides/alphainverse) jest równy bieżącemu [AlphaInverse](../../com.aspose.slides/alphainverse).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaInverse](../../com.aspose.slides/alphainverse) to compare. |

**Zwraca:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Działa jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - A hash code for the current object.