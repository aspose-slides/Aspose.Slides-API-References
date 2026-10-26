---
title: SoftEdge
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een zacht rand-effect.
type: docs
url: /nl/com.aspose.slides/softedge/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Vertegenwoordigt een zacht rand-effect. De randen van de vorm zijn onscherp, terwijl de vulling niet wordt beïnvloed.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRadius()](#getRadius--) | Specificeert de radius van de vervaging die op de randen moet worden toegepast. |
| [setRadius(double value)](#setRadius-double-) | Specificeert de radius van de vervaging die op de randen moet worden toegepast. |
| [getEffective()](#getEffective--) | Haalt effectieve Soft Edge effect-gegevens op met de overerving toegepast. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [SoftEdge](../../com.aspose.slides/softedge) gelijk is aan de huidige [SoftEdge](../../com.aspose.slides/softedge). |
| [hashCode()](#hashCode--) | Dient als een hash-functie voor een bepaald type. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Specificeert de radius van de vervaging die op de randen moet worden toegepast. Lezen/schrijven double.

**Retour:**  
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Specificeert de radius van de vervaging die op de randen moet worden toegepast. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Haalt effectieve Soft Edge effect-gegevens op met de overerving toegepast.

**Retour:**  
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - Een [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
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

Bepaalt of de opgegeven [SoftEdge](../../com.aspose.slides/softedge) gelijk is aan de huidige [SoftEdge](../../com.aspose.slides/softedge).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [SoftEdge](../../com.aspose.slides/softedge) om te vergelijken. |

**Retour:**  
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als een hash-functie voor een bepaald type.

**Retour:**  
int - Een hashcode voor het huidige object.