---
title: Glow
second_title: Aspose.Slides for Java API referencia
description: Egy Glow hatást reprezentál, amelyben egy színes elmosódott körvonalat adnak hozzá az objektum széleihez kívül.
type: docs
url: /hu/com.aspose.slides/glow/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

A Glow hatást reprezentálja, amelyben egy színes elmosódott körvonalat adnak hozzá az objektum széleihez kívül.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRadius()](#getRadius--) | Sugár. |
| [setRadius(double value)](#setRadius-double-) | Sugár. |
| [getColor()](#getColor--) | Színformátum. |
| [getEffective()](#getEffective--) | A származtatással alkalmazott hatékony Glow effektus adatot adja vissza. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [Glow](../../com.aspose.slides/glow) megegyezik-e az aktuális [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Sugár. Olvasás/írás  double .

**Visszatér:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Sugár. Olvasás/írás  double .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Színformátum. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


A származtatással alkalmazott hatékony Glow effektus adatot adja vissza.

**Visszatér:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
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


Megállapítja, hogy a megadott [Glow](../../com.aspose.slides/glow) megegyezik-e az aktuális [Glow](../../com.aspose.slides/glow).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [Glow](../../com.aspose.slides/glow) a összehasonlításhoz. |

**Visszatér:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatér:**
int - Egy hash kód az aktuális objektumhoz.