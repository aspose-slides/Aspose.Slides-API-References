---
title: Glow
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Glow-effect voor waarbij een kleurvervaging langs de randen van het object wordt toegevoegd.
type: docs
url: /nl/com.aspose.slides/glow/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Stelt een Glow-effect voor, waarbij een kleurvervaging langs de randen van het object wordt toegevoegd.
## Methoden

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Straal. |
| [setRadius(double value)](#setRadius-double-) | Straal. |
| [getColor()](#getColor--) | Kleuropslag. |
| [getEffective()](#getEffective--) | Haalt effectieve Glow-effectgegevens op met de geërfde instellingen toegepast. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [Glow](../../com.aspose.slides/glow) gelijk is aan de huidige [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Dient als hash-functie voor een specifiek type. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Straal. Alleen-lezen? double .

**Retour:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Straal. Lezen/schrijven double .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Kleuropslag. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

Haalt effectieve Glow-effectgegevens op met de geërfde instellingen toegepast.

**Retour:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - Een [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
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

Versie. Alleen-lezen long.

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
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Het [Glow](../../com.aspose.slides/glow) om te vergelijken. |

**Retour:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als hash-functie voor een specifiek type.

**Retour:**
int - A hash code for the current object.