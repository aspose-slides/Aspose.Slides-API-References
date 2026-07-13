---
title: SoftEdge
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Representuje efekt měkkých okrajů.
type: docs
url: /cs/com.aspose.slides/softedge/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Reprezentuje efekt měkkých okrajů. Okraje tvaru jsou rozmazané, zatímco výplň není ovlivněna.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRadius()](#getRadius--) | Určuje poloměr rozostření aplikovaný na okraje. |
| [setRadius(double value)](#setRadius-double-) | Určuje poloměr rozostření aplikovaný na okraje. |
| [getEffective()](#getEffective--) | Získá efektivní data měkkých okrajů s aplikovaným děděním. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je specifikovaný [SoftEdge](../../com.aspose.slides/softedge) roven aktuálnímu [SoftEdge](../../com.aspose.slides/softedge). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Určuje poloměr rozostření aplikovaný na okraje. Čtení/zápis double.

**Vrací:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Určuje poloměr rozostření aplikovaný na okraje. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```


Získá efektivní data měkkých okrajů s aplikovaným děděním.

**Vrací:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Verze. Pouze ke čtení long.

**Vrací:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Vrací rodiče IPresentationComponent. Pouze ke čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Určuje, zda je specifikovaný [SoftEdge](../../com.aspose.slides/softedge) roven aktuálnímu [SoftEdge](../../com.aspose.slides/softedge).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt [SoftEdge](../../com.aspose.slides/softedge) pro porovnání. |

**Vrací:**
boolean - true pokud jsou objekty stejné; v opačném případě false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - hash kód pro aktuální objekt.