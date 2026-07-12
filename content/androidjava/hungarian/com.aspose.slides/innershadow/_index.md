---
title: InnerShadow
second_title: Aspose.Slides Androidra a Java API hivatkozás segítségével
description: Egy belső árnyék effektust reprezentál.
type: docs
url: /hu/com.aspose.slides/innershadow/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Egy belső árnyék effektust reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Elmosódási sugár. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Elmosódási sugár. |
| [getDirection()](#getDirection--) | Árnyék iránya. |
| [setDirection(float value)](#setDirection-float-) | Árnyék iránya. |
| [getDistance()](#getDistance--) | Árnyék távolsága. |
| [setDistance(double value)](#setDistance-double-) | Árnyék távolsága. |
| [getShadowColor()](#getShadowColor--) | Árnyék színe. |
| [getEffective()](#getEffective--) | Megkapja a hatékony belső árnyék effektus adatokat az öröklődés alkalmazásával. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a megadott [InnerShadow](../../com.aspose.slides/innershadow) egyenlő-e a jelenlegi [InnerShadow](../../com.aspose.slides/innershadow)-vel. |
| [hashCode()](#hashCode--) | Hasítófüggvényként szolgál egy adott típushoz. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```


Elmosódási sugár. Olvasás/írás double.

**Visszatér:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```


Elmosódási sugár. Olvasás/írás double.

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


Árnyék színe. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```


Megkapja a hatékony belső árnyék effektus adatokat az öröklődés alkalmazásával.

**Visszatér:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - A [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Verzió. Csak olvasható long.

**Visszatér:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Visszaadja a szülő IPresentationComponent-et. Csak olvasható [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Visszatér:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Meghatározza, hogy a megadott [InnerShadow](../../com.aspose.slides/innershadow) egyenlő-e a jelenlegi [InnerShadow](../../com.aspose.slides/innershadow)-vel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [InnerShadow](../../com.aspose.slides/innershadow) az összehasonlításhoz. |

**Visszatér:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hasítófüggvényként szolgál egy adott típushoz.

**Visszatér:**
int - A jelenlegi objektum hash kódja.