---
title: BiLevel
second_title: Aspose.Slides pro Java – referenční API
description: Představuje dvoustupňový černobílý efekt.
type: docs
url: /cs/com.aspose.slides/bilevel/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Představuje efekt dvoustupňový (černobílý). Vstupní barvy, jejichž luminance je menší než zadaná prahová hodnota, jsou změněny na černou. Vstupní barvy, jejichž luminance je větší nebo rovna zadané hodnotě, jsou nastaveny na bílou. Hodnoty alfa efektu tímto efektem nejsou ovlivněny.
## Metody

| Metoda | Popis |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Bi-Level effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [BiLevel](../../com.aspose.slides/bilevel) is equal to the current [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


Získá efektivní data Bi-Level s aplikovaným děděním.

**Vrací:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Určuje, zda je zadaný [BiLevel](../../com.aspose.slides/bilevel) roven aktuálnímu [BiLevel](../../com.aspose.slides/bilevel).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [BiLevel](../../com.aspose.slides/bilevel) k porovnání. |

**Vrací:**
boolean - true, pokud jsou objekty rovny; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - Hash kód pro aktuální objekt.