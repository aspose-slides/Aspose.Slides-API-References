---
title: SoftEdge
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Weichkanteneffekt dar.
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

Stellt einen Weichkanteneffekt dar. Die Kanten der Form sind verschwommen, während die Füllung nicht beeinflusst wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRadius()](#getRadius--) | Gibt den Radius der Unschärfe an, der auf die Kanten angewendet wird. |
| [setRadius(double value)](#setRadius-double-) | Gibt den Radius der Unschärfe an, der auf die Kanten angewendet wird. |
| [getEffective()](#getEffective--) | Ruft die effektiven Soft Edge-Effekt-Daten mit angewandter Vererbung ab. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [SoftEdge](../../com.aspose.slides/softedge) dem aktuellen [SoftEdge](../../com.aspose.slides/softedge) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Gibt den Radius der Unschärfe an, der auf die Kanten angewendet wird. Lese-/Schreibzugriff double.

**Rückgabewert:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Gibt den Radius der Unschärfe an, der auf die Kanten angewendet wird. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Ruft die effektiven Soft Edge-Effekt-Daten mit angewandter Vererbung ab.

**Rückgabewert:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Rückgabe des Parent_Immediate-Objekts. Nur-Lesezugriff IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Nur-Lesezugriff long.

**Rückgabewert:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Rückgabe des übergeordneten IPresentationComponent. Nur-Lesezugriff [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

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
| obj | java.lang.Object | Das [SoftEdge](../../com.aspose.slides/softedge) zum Vergleichen. |

**Rückgabewert:**
boolean - true, wenn Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabewert:**
int - Ein Hashcode für das aktuelle Objekt.