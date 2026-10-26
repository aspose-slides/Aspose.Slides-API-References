---
title: AlphaInverse
second_title: Aspose.Slides dla Androida - odwołanie do API Java
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

Reprezentuje efekt odwrotnego alfa. Wartości alfa (przezroczystość) są odwracane przez odjęcie od 100%.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera efektywne dane efektu odwrotnego alfa z uwzględnieniem dziedziczenia. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy podany [AlphaInverse](../../com.aspose.slides/alphainverse) jest równy bieżącemu [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


Pobiera efektywne dane efektu odwrotnego alfa z uwzględnieniem dziedziczenia.

**Zwraca:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu, long.

**Zwraca:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Określa, czy podany [AlphaInverse](../../com.aspose.slides/alphainverse) jest równy bieżącemu [AlphaInverse](../../com.aspose.slides/alphainverse).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt [AlphaInverse](../../com.aspose.slides/alphainverse) do porównania. |

**Zwraca:**
boolean - true, jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Skrót (hash code) bieżącego obiektu.