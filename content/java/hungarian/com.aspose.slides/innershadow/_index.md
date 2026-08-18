---
title: InnerShadow
second_title: Aspose.Slides Java API hivatkozás
description: Belső árnyék hatást képvisel.
type: docs
url: /hu/com.aspose.slides/innershadow/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Represents a Inner Shadow effect.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Elmosási sugár. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Elmosási sugár. |
| [getDirection()](#getDirection--) | Árnyék iránya. |
| [setDirection(float value)](#setDirection-float-) | Árnyék iránya. |
| [getDistance()](#getDistance--) | Árnyék távolsága. |
| [setDistance(double value)](#setDistance-double-) | Árnyék távolsága. |
| [getShadowColor()](#getShadowColor--) | Árnyék színe. |
| [getEffective()](#getEffective--) | Lekérdezi a hatékony Inner Shadow hatásadatokat az öröklődés alkalmazásával. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [InnerShadow](../../com.aspose.slides/innershadow) megegyezik-e a jelenlegi [InnerShadow](../../com.aspose.slides/innershadow)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```


Elmosási sugár. Olvasás/írás double.

**Visszatér:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```


Elmosási sugár. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```


Árnyék iránya. Olvasás/írás float.

**Visszatér:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Árnyék iránya. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Árnyék távolsága. Olvasás/írás double.

**Visszatér:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Árnyék távolsága. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


Árnyék színe. Csak olvasás [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```


Lekérdezi a hatékony Inner Shadow hatásadatokat az öröklődés alkalmazásával.

**Visszatér:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - A [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszatér a Parent_Immediate objektummal. Csak olvasás IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Verzió. Csak olvasás long.

**Visszatér:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Visszatér a szülő IPresentationComponent objektummal. Csak olvasás [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Visszatér:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott [InnerShadow](../../com.aspose.slides/innershadow) megegyezik-e a jelenlegi [InnerShadow](../../com.aspose.slides/innershadow)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [InnerShadow](../../com.aspose.slides/innershadow) a összehasonlításhoz. |

**Visszatér:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatér:**
int - A hash kód a jelenlegi objektumhoz.