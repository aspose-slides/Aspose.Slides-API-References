---
title: FillOverlay
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Fill Overlay effect voor.
type: docs
url: /nl/com.aspose.slides/filloverlay/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Representeert een Fill Overlay effect. Een fill overlay kan worden gebruikt om een extra vulling voor een object op te geven en de twee vullingen samen te voegen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill format. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Gets effective Fill Overlay effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [FillOverlay](../../com.aspose.slides/filloverlay) gelijk is aan de huidige [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Dient als een hash-functie voor een bepaald type. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Fill format. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. Lezen/Schrijven [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Retour:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```


FillBlendMode. Lezen/Schrijven [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


Haalt effectieve Fill Overlay effectgegevens op met de erfenis toegepast.

**Retour:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - een [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of de opgegeven [FillOverlay](../../com.aspose.slides/filloverlay) gelijk is aan de huidige [FillOverlay](../../com.aspose.slides/filloverlay).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het [FillOverlay](../../com.aspose.slides/filloverlay) om te vergelijken. |

**Retour:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als een hash-functie voor een bepaald type.

**Retour:**
int - Een hashcode voor het huidige object.