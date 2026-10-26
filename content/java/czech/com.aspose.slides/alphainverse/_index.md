---
title: AlphaInverse
second_title: Aspose.Slides pro Java - referenční příručka API
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

Reprezentuje efekt Inverzní alfa. Hodnoty alfa (neprůhlednost) jsou invertovány odečtením od 100%.

## Metody

| Metoda | Popis |
| --- | --- |
| [getEffective()](#getEffective--) | Získá data efektivního efektu Inverzní alfa s aplikovaným děděním. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [AlphaInverse](../../com.aspose.slides/alphainverse) roven aktuálnímu [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Slouží jako hash funkce pro konkrétní typ. |

### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Získá data efektivního efektu Inverzní alfa s aplikovaným děděním.

**Návratová hodnota:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).

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

Určuje, zda je zadaný [AlphaInverse](../../com.aspose.slides/alphainverse) roven aktuálnímu [AlphaInverse](../../com.aspose.slides/alphainverse).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt [AlphaInverse](../../com.aspose.slides/alphainverse) pro porovnání. |

**Návratová hodnota:**
boolean – true pokud jsou objekty rovny; jinak false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hash funkce pro konkrétní typ.

**Návratová hodnota:**
int – hash kód pro aktuální objekt.