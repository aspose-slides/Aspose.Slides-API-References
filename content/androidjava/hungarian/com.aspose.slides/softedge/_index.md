---
title: SoftEdge
second_title: Aspose.Slides Androidhoz Java API referencia
description: Egy puha szegélyhatást képvisel.
type: docs
url: /hu/com.aspose.slides/softedge/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Egy puha szegélyhatást képvisel. Az alakzat szélei elmosódnak, míg a kitöltés nem változik.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRadius()](#getRadius--) | Megadja a szélekre alkalmazandó elmosódás sugarát. |
| [setRadius(double value)](#setRadius-double-) | Megadja a szélekre alkalmazandó elmosódás sugarát. |
| [getEffective()](#getEffective--) | Lekéri a hatékony Soft Edge effektus adatokat az öröklődés alkalmazásával. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a megadott [SoftEdge](../../com.aspose.slides/softedge) egyenlő-e a jelenlegi [SoftEdge](../../com.aspose.slides/softedge)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Megadja a szélekre alkalmazandó elmosódás sugarát. Olvasás/írás double.

**Visszatér:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Megadja a szélekre alkalmazandó elmosódás sugarát. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Lekéri a hatékony Soft Edge effektus adatokat az öröklődés alkalmazásával.

**Visszatér:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
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

Meghatározza, hogy a megadott [SoftEdge](../../com.aspose.slides/softedge) egyenlő-e a jelenlegi [SoftEdge](../../com.aspose.slides/softedge)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [SoftEdge](../../com.aspose.slides/softedge) a összehasonlításhoz. |

**Visszatér:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatér:**
int - A hash kód a jelenlegi objektumhoz.