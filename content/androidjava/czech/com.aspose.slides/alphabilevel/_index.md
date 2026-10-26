---
title: AlphaBiLevel
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje efekt Alpha Bi-Level.
type: docs
url: /cs/com.aspose.slides/alphabilevel/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechny implementované rozhraní:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Representuje efekt Alpha Bi-Level. Hodnoty Alpha (Opacity) menší než práh jsou změněny na 0 (zcela průhledné) a hodnoty Alpha větší nebo rovny prahu jsou změněny na 100 % (zcela neprůhledné).
## Metody

| Metoda | Popis |
| --- | --- |
| [getThreshold()](#getThreshold--) | Vrací práh efektu. |
| [setThreshold(float value)](#setThreshold-float-) | Vrací práh efektu. |
| [getEffective()](#getEffective--) | Získává efektivní data Alpha Bi-Level s aplikovanou dědičností. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [AlphaBiLevel](../../com.aspose.slides/alphabilevel) roven aktuálnímu [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Vrací práh efektu. Čtení/Zápis float.

**Vrací:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Vrací práh efektu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Získává efektivní data Alpha Bi-Level s aplikovanou dědičností.

**Vrací:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda je zadaný [AlphaBiLevel](../../com.aspose.slides/alphabilevel) roven aktuálnímu [AlphaBiLevel](../../com.aspose.slides/alphabilevel).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaBiLevel](../../com.aspose.slides/alphabilevel) k porovnání. |

**Vrací:**
boolean - true pokud jsou objekty stejné; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - Hash kód pro aktuální objekt.