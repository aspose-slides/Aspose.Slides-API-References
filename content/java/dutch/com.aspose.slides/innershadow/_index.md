---
title: InnerShadow
second_title: Aspose.Slides voor Java API-referentie
description: Representeert een Inner Shadow-effect.
type: docs
url: /nl/com.aspose.slides/innershadow/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Stelt een Inner Shadow-effect voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Vervagingsstraal. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Vervagingsstraal. |
| [getDirection()](#getDirection--) | Richting van de schaduw. |
| [setDirection(float value)](#setDirection-float-) | Richting van de schaduw. |
| [getDistance()](#getDistance--) | Afstand van de schaduw. |
| [setDistance(double value)](#setDistance-double-) | Afstand van de schaduw. |
| [getShadowColor()](#getShadowColor--) | Kleur van de schaduw. |
| [getEffective()](#getEffective--) | Haalt effectieve Inner Shadow-effectgegevens op met de toegepaste erfelijkheid. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [InnerShadow](../../com.aspose.slides/innershadow) gelijk is aan de huidige [InnerShadow](../../com.aspose.slides/innershadow). |
| [hashCode()](#hashCode--) | Dient als hash-functie voor een specifiek type. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```


Vervagingsstraal. Alleen-lezen double.

**Retourwaarde:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```


Vervagingsstraal. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```


Richting van de schaduw. Lezen/Schrijven float.

**Retourwaarde:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Richting van de schaduw. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Afstand van de schaduw. Lezen/Schrijven double.

**Retourwaarde:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Afstand van de schaduw. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


Kleur van de schaduw. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourwaarde:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```


Haalt effectieve Inner Shadow-effectgegevens op met de toegepaste erfelijkheid.

**Retourwaarde:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - A [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourwaarde:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versie. Alleen-lezen long.

**Retourwaarde:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Retourneert parent IPresentationComponent. Alleen-lezen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retourwaarde:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of de opgegeven [InnerShadow](../../com.aspose.slides/innershadow) gelijk is aan de huidige [InnerShadow](../../com.aspose.slides/innershadow).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het [InnerShadow](../../com.aspose.slides/innershadow) om te vergelijken. |

**Retourwaarde:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als hash-functie voor een specifiek type.

**Retourwaarde:**
int - Een hashcode voor het huidige object.