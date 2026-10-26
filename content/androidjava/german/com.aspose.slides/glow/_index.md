---
title: Glow
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Glow-Effekt dar, bei dem ein farbiger unscharfer Umriss außerhalb der Kanten des Objekts hinzugefügt wird.
type: docs
url: /de/com.aspose.slides/glow/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Stellt einen Glow-Effekt dar, bei dem ein unscharfer farbiger Umriss außerhalb der Kanten des Objekts hinzugefügt wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Farbformat. |
| [getEffective()](#getEffective--) | Ruft die wirksamen Glow-Effekt-Daten mit angewandter Vererbung ab. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [Glow](../../com.aspose.slides/glow) dem aktuellen [Glow](../../com.aspose.slides/glow) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Radius. Lesen/Schreiben  double .

**Rückgabe:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Radius. Lesen/Schreiben  double .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Farbformat. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

Ruft die wirksamen Glow-Effekt-Daten mit angewandter Vererbung ab.

**Rückgabe:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - Ein [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Nur-Lesen long.

**Rückgabe:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Gibt das übergeordnete IPresentationComponent zurück. Nur-Lesen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Rückgabe:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [Glow](../../com.aspose.slides/glow) dem aktuellen [Glow](../../com.aspose.slides/glow) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [Glow](../../com.aspose.slides/glow) zum Vergleichen. |

**Rückgabe:**
boolean - true, wenn Objekte gleich sind; sonst false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hashcode für das aktuelle Objekt.