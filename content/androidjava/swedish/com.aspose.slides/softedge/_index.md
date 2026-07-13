---
title: SoftEdge
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en mjuk kant-effekt.
type: docs
url: /sv/com.aspose.slides/softedge/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Representerar en mjuk kant-effekt. Kanten på formen är suddig, medan fyllningen inte påverkas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRadius()](#getRadius--) | Anger suddradien som ska tillämpas på kanterna. |
| [setRadius(double value)](#setRadius-double-) | Anger suddradien som ska tillämpas på kanterna. |
| [getEffective()](#getEffective--) | Hämtar effektiv Soft Edge-effektdata med arv tillämpat. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om den angivna [SoftEdge](../../com.aspose.slides/softedge) är lika med den aktuella [SoftEdge](../../com.aspose.slides/softedge). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Anger suddradien som ska tillämpas på kanterna. Läs/skriv double.

**Returnerar:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Anger suddradien som ska tillämpas på kanterna. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```


Hämtar effektiv Soft Edge-effektdata med arv tillämpat.

**Returnerar:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - En [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Returnerar föräldern IPresentationComponent. Skrivskyddad [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returnerar:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Avgör om den angivna [SoftEdge](../../com.aspose.slides/softedge) är lika med den aktuella [SoftEdge](../../com.aspose.slides/softedge).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [SoftEdge](../../com.aspose.slides/softedge) som ska jämföras. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hash-kod för det aktuella objektet.