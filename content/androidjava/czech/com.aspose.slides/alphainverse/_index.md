---
title: AlphaInverse
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje efekt Alpha Inverse.
type: docs
url: /cs/com.aspose.slides/alphainverse/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechny implementované rozhraní:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Reprezentuje efekt Alpha Inverse. Hodnoty Alpha (průhlednost) jsou invertovány odečtením od 100 %.

## Metody

| Metoda | Popis |
| --- | --- |
| [getEffective()](#getEffective--) | Získá efektivní data Alpha Inverse efektu s aplikovaným děděním. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda zadaný [AlphaInverse](../../com.aspose.slides/alphainverse) je roven aktuálnímu [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


Získá efektivní data Alpha Inverse efektu s aplikovaným děděním.

**Návratová hodnota:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - Jedna [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verze. Pouze pro čtení long.

**Návratová hodnota:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Určuje, zda zadaný [AlphaInverse](../../com.aspose.slides/alphainverse) je roven aktuálnímu [AlphaInverse](../../com.aspose.slides/alphainverse).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaInverse](../../com.aspose.slides/alphainverse) k porovnání. |

**Návratová hodnota:**
boolean - true pokud jsou objekty rovny; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hashovací funkce pro konkrétní typ.

**Návratová hodnota:**
int - Hashovací kód pro aktuální objekt.