---
title: Glow
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een Glow-effect voor waarbij een kleurvervagende omtrek buiten de randen van het object wordt toegevoegd.
type: docs
url: /nl/com.aspose.slides/glow/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Stelt een Glow-effect voor, waarbij een kleurvervagende omtrek buiten de randen van het object wordt toegevoegd.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Kleurindeling. |
| [getEffective()](#getEffective--) | Haalt de effectieve Glow-effectgegevens op met de toegepaste overerving. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [Glow](../../com.aspose.slides/glow) gelijk is aan de huidige [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Dient als een hashfunctie voor een specifiek type. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Radius. Lezen/schrijven  double .

**Retour:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Radius. Lezen/schrijven  double .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Kleurindeling. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Haalt de effectieve Glow-effectgegevens op met de toegepaste overerving.

**Retour:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - een [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Alleen-lezen long.

**Retour:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Retourneert ouder IPresentationComponent. Alleen-lezen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retour:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of de opgegeven [Glow](../../com.aspose.slides/glow) gelijk is aan de huidige [Glow](../../com.aspose.slides/glow).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [Glow](../../com.aspose.slides/glow) om te vergelijken. |

**Retour:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als een hashfunctie voor een specifiek type.

**Retour:**
int - Een hashcode voor het huidige object.