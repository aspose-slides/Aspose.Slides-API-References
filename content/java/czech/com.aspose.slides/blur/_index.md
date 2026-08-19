---
title: Blur
second_title: Aspose.Slides pro Java - referenční příručka API
description: Zastupuje efekt Blur, který se použije na celý tvar včetně jeho výplně.
type: docs
url: /cs/com.aspose.slides/blur/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Představuje efekt Blur, který se použije na celý tvar, včetně výplně. Všechny barevné kanály, včetně alfy, jsou ovlivněny.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRadius()](#getRadius--) | Vrací nebo nastavuje poloměr rozostření. |
| [setRadius(double value)](#setRadius-double-) | Vrací nebo nastavuje poloměr rozostření. |
| [getGrow()](#getGrow--) | Určuje, zda by se měly ohraničující oblasti objektu zvětšit v důsledku rozostření. |
| [setGrow(boolean value)](#setGrow-boolean-) | Určuje, zda by se měly ohraničující oblasti objektu zvětšit v důsledku rozostření. |
| [getEffective()](#getEffective--) | Získá efektivní data efektu Blur s aplikovaným děděním. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [Blur](../../com.aspose.slides/blur) roven aktuálnímu [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Vrací nebo nastavuje poloměr rozostření. Čtení/zápis double.

**Vrací:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Vrací nebo nastavuje poloměr rozostření. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Určuje, zda by se měly ohraničující oblasti objektu zvětšit v důsledku rozostření. True naznačuje, že jsou ohraničení zvětšena, zatímco false značí, že nejsou. Čtení/zápis boolean.

**Vrací:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Určuje, zda by se měly ohraničující oblasti objektu zvětšit v důsledku rozostření. True naznačuje, že jsou ohraničení zvětšena, zatímco false značí, že nejsou. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Získá efektivní data efektu Blur s aplikovaným děděním.

**Vrací:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) – [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda je zadaný [Blur](../../com.aspose.slides/blur) roven aktuálnímu [Blur](../../com.aspose.slides/blur).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt [Blur](../../com.aspose.slides/blur) k porovnání. |

**Vrací:**
boolean - true pokud jsou objekty stejné; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - Hash kód pro aktuální objekt.