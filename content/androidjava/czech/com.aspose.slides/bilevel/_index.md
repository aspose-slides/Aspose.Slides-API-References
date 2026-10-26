---
title: BiLevel
second_title: Aspose.Slides pro Android přes Java API referenci
description: Representuje Bi-Level černobílý efekt.
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

Reprezentuje Bi-Level (černobílý) efekt. Vstupní barvy, jejichž luminance je menší než zadaná prahová hodnota, jsou změněny na černou. Vstupní barvy, jejichž luminance je větší nebo rovna zadané hodnotě, jsou nastaveny na bílou. Hodnoty alfa efektu nejsou tímto efektem ovlivněny.

## Metody

| Metoda | Popis |
| --- | --- |
| [getEffective()](#getEffective--) | Získá efektivní data Bi-Level efektu s aplikovanou dědičností. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [BiLevel](../../com.aspose.slides/bilevel) roven aktuálnímu [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


Získá efektivní data Bi-Level efektu s aplikovanou dědičností.

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
| obj | java.lang.Object | Objekt [BiLevel](../../com.aspose.slides/bilevel) k porovnání. |

**Vrací:**
boolean – true, pokud jsou objekty stejné; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int – hash kód pro aktuální objekt.