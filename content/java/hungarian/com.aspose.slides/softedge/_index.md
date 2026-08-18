---
title: SoftEdge
second_title: Aspose.Slides for Java API referencia
description: Lágy szegély hatást képvisel.
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

Egy lágy szegély hatást képvisel. A forma szélei elmosódottak, míg a kitöltés nem változik.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRadius()](#getRadius--) | Specifies the radius of blur to apply to the edges. |
| [setRadius(double value)](#setRadius-double-) | Specifies the radius of blur to apply to the edges. |
| [getEffective()](#getEffective--) | Gets effective Soft Edge effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [SoftEdge](../../com.aspose.slides/softedge) is equal to the current [SoftEdge](../../com.aspose.slides/softedge). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

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

Lekéri a hatásos Soft Edge adatokat az öröklődés alkalmazásával.

**Visszatér:**  
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) – A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaad egy Parent_Immediate objektumot. Csak olvasható IDOMObject.

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

Megállapítja, hogy a megadott [SoftEdge](../../com.aspose.slides/softedge) egyenlő-e a jelenlegi [SoftEdge](../../com.aspose.slides/softedge).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [SoftEdge](../../com.aspose.slides/softedge) a összehasonlításhoz. |

**Visszatér:**  
boolean – true ha az objektumok egyenlőek; különben false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Szolgál hash függvényként egy adott típushoz.

**Visszatér:**  
int – Egy hash kód a jelenlegi objektum számára.