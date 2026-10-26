---
title: Glow
second_title: Aspose.Slides för Java API-referens
description: Representerar en Glow-effekt där en färgad suddig kontur läggs till utanför objektets kanter.
type: docs
url: /sv/com.aspose.slides/glow/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Representerar en Glow-effekt, där en färgad suddig kontur läggs till utanför objektets kanter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Färgformat. |
| [getEffective()](#getEffective--) | Hämtar effektiva Glow-effektsdata med arv tillämpat. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den angivna [Glow](../../com.aspose.slides/glow) är lika med den aktuella [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Radius. Läs/skriv double .

**Returnerar:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Radius. Läs/skriv double .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Färgformat. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Hämtar effektiva Glow-effektsdata med arv tillämpat.

**Returnerar:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
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


Returnerar förälder IPresentationComponent. Skrivskyddad [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returnerar:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om den angivna [Glow](../../com.aspose.slides/glow) är lika med den aktuella [Glow](../../com.aspose.slides/glow).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [Glow](../../com.aspose.slides/glow) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.