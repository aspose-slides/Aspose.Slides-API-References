---
title: AlphaCeiling
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje efekt Alpha Ceiling.
type: docs
url: /cs/com.aspose.slides/alphaceiling/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechny implementované rozhraní:**
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

Representuje efekt Alpha Ceiling. Hodnoty Alpha (průhlednost) větší než nula jsou změněny na 100 %. Jinými slovy, vše, co je částečně neprůhledné, se stane zcela neprůhledným.
## Metody

| Metoda | Popis |
| --- | --- |
| [getEffective()](#getEffective--) | Získá efektivní data Alpha Ceiling s aplikovaným děděním. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [AlphaCeiling](../../com.aspose.slides/alphaceiling) roven aktuálnímu [AlphaCeiling](../../com.aspose.slides/alphaceiling). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```

Získá efektivní data Alpha Ceiling s aplikovaným děděním.

**Vrací:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda je zadaný [AlphaCeiling](../../com.aspose.slides/alphaceiling) roven aktuálnímu [AlphaCeiling](../../com.aspose.slides/alphaceiling).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaCeiling](../../com.aspose.slides/alphaceiling) k porovnání. |

**Vrací:**
boolean - true, pokud jsou objekty stejné; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - hash kód pro aktuální objekt.