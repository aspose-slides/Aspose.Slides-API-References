---
title: PVIObject
second_title: Aspose.Slides voor Android via Java API-referentie
description: Omvat basisservice-infrastructuur voor objecten die onderwerp kunnen zijn van eigenschapswaarde-erfenis.
type: docs
url: /nl/com.aspose.slides/pviobject/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Omvat basisservice-infrastructuur voor objecten die onderwerp kunnen zijn van eigenschapswaarde-erfenis.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Vergelijkt met opgegeven object. |
| [hashCode()](#hashCode--) | Retourneert hashcode. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retourneert:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```


Retourneert ouder IPresentationComponent. Alleen-lezen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retourneert:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```




**Retourneert:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```


Retourneert de basisdia. Alleen-lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retourneert:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```


Retourneert de presentatie. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Vergelijkt met opgegeven object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Object om te vergelijken. |

**Retourneert:**
boolean - Waar als objecten gelijk zijn, anders onwaar.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert hashcode.

**Retourneert:**
int - Hashcode.