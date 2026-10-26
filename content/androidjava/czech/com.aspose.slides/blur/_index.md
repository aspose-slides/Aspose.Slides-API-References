---
title: Blur
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje efekt rozostření, který se použije na celý tvar včetně jeho výplně.
type: docs
url: /cs/com.aspose.slides/blur/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechny implementované rozhraní:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Represents a Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRadius()](#getRadius--) | Vrací nebo nastavuje poloměr rozostření. |
| [setRadius(double value)](#setRadius-double-) | Vrací nebo nastavuje poloměr rozostření. |
| [getGrow()](#getGrow--) | Určuje, zda by měly být ohraničení objektu zvětšeny v důsledku rozostření. |
| [setGrow(boolean value)](#setGrow-boolean-) | Určuje, zda by měly být ohraničení objektu zvětšeny v důsledku rozostření. |
| [getEffective()](#getEffective--) | Získá efektivní data efektu rozostření s aplikovaným děděním. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [Blur](../../com.aspose.slides/blur) roven aktuálnímu [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Vrací nebo nastavuje poloměr rozostření. Čtení/Zápis double.

**Vrací:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Vrací nebo nastavuje poloměr rozostření. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


Určuje, zda by měly být ohraničení objektu zvětšeny v důsledku rozostření. True indicates the bounds are grown while false indicates that they are not. Čtení/Zápis boolean.

**Vrací:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


Určuje, zda by měly být ohraničení objektu zvětšeny v důsledku rozostření. True indicates the bounds are grown while false indicates that they are not. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


Získá efektivní data efektu rozostření s aplikovaným děděním.

**Vrací:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - Jedná se o [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Určuje, zda je zadaný [Blur](../../com.aspose.slides/blur) roven aktuálnímu [Blur](../../com.aspose.slides/blur).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [Blur](../../com.aspose.slides/blur) k porovnání. |

**Vrací:**
boolean – true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - A hash code for the current object.