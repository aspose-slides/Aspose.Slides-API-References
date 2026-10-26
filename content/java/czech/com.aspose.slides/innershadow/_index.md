---
title: InnerShadow
second_title: Aspose.Slides pro Java API Reference
description: Representuje efekt vnitřního stínu.
type: docs
url: /cs/com.aspose.slides/innershadow/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Representuje efekt vnitřního stínu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Poloměr rozostření. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Poloměr rozostření. |
| [getDirection()](#getDirection--) | Směr stínu. |
| [setDirection(float value)](#setDirection-float-) | Směr stínu. |
| [getDistance()](#getDistance--) | Vzdálenost stínu. |
| [setDistance(double value)](#setDistance-double-) | Vzdálenost stínu. |
| [getShadowColor()](#getShadowColor--) | Barva stínu. |
| [getEffective()](#getEffective--) | Získá efektivní data efektu vnitřního stínu s aplikovaným děděním. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [InnerShadow](../../com.aspose.slides/innershadow) roven aktuálnímu [InnerShadow](../../com.aspose.slides/innershadow). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro určitý typ. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Poloměr rozostření. Číst/zapisovat double.

**Vrací:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Poloměr rozostření. Číst/zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Směr stínu. Číst/zapisovat float.

**Vrací:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Směr stínu. Číst/zapisovat float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Vzdálenost stínu. Číst/zapisovat double.

**Vrací:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Vzdálenost stínu. Číst/zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Barva stínu. Jen ke čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```

Získá efektivní data efektu vnitřního stínu s aplikovaným děděním.

**Vrací:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - A [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent\_Immediate. Jen ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Verze. Jen ke čtení long.

**Vrací:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Vrací nadřazený IPresentationComponent. Jen ke čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda je zadaný [InnerShadow](../../com.aspose.slides/innershadow) roven aktuálnímu [InnerShadow](../../com.aspose.slides/innershadow).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [InnerShadow](../../com.aspose.slides/innershadow) k porovnání. |

**Vrací:**
boolean - true pokud jsou objekty rovny; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro určitý typ.

**Vrací:**
int - Hash kód pro aktuální objekt.