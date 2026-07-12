---
title: SoftEdge
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Soft Edge-Effekt dar.
type: docs
url: /de/com.aspose.slides/softedge/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Stellt einen Soft Edge-Effekt dar. Die Kanten der Form sind unscharf, während die Füllung nicht beeinflusst wird.
## Methoden

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Gibt den Radius der Unschärfe an, der auf die Kanten angewendet wird. |
| [setRadius(double value)](#setRadius-double-) | Gibt den Radius der Unschärfe an, der auf die Kanten angewendet wird. |
| [getEffective()](#getEffective--) | Ruft wirksame Soft Edge-Effektdaten mit angewandter Vererbung ab. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [SoftEdge](../../com.aspose.slides/softedge) dem aktuellen [SoftEdge](../../com.aspose.slides/softedge) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Gibt den Radius der Unschärfe an, der auf die Kanten angewendet wird. Lese/Schreib double.

**Rückgabewert:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Gibt den Radius der Unschärfe an, der auf die Kanten angewendet wird. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```


Ruft wirksame Soft Edge-Effektdaten mit angewandter Vererbung ab.

**Rückgabewert:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Schreibgeschützt IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Schreibgeschützt long.

**Rückgabewert:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Gibt das übergeordnete IPresentationComponent zurück. Schreibgeschützt [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Rückgabewert:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene [SoftEdge](../../com.aspose.slides/softedge) dem aktuellen [SoftEdge](../../com.aspose.slides/softedge) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [SoftEdge](../../com.aspose.slides/softedge) zum Vergleich. |

**Rückgabewert:**
boolean - true, wenn die Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabewert:**
int - Ein Hashcode für das aktuelle Objekt.