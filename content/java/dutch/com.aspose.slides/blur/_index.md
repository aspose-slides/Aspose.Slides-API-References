---
title: Blur
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een Blur-effect voor dat wordt toegepast op de volledige vorm, inclusief de vulling.
type: docs
url: /nl/com.aspose.slides/blur/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Stelt een Blur effect voor dat wordt toegepast op de volledige vorm, inclusief de vulling. Alle kleurkanalen, inclusief alfa, worden beïnvloed.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRadius()](#getRadius--) | Geeft de vervagingsstraal terug of stelt deze in. |
| [setRadius(double value)](#setRadius-double-) | Geeft de vervagingsstraal terug of stelt deze in. |
| [getGrow()](#getGrow--) | Bepaalt of de grenzen van het object moeten worden uitgebreid als gevolg van de vervaging. |
| [setGrow(boolean value)](#setGrow-boolean-) | Bepaalt of de grenzen van het object moeten worden uitgebreid als gevolg van de vervaging. |
| [getEffective()](#getEffective--) | Haalt effectieve Blur effectgegevens op met de erfenis toegepast. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [Blur](../../com.aspose.slides/blur) gelijk is aan de huidige [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Dient als hash-functie voor een bepaald type. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Geeft de vervagingsstraal terug of stelt deze in. Lezen/Schrijven double.

**Retour:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Geeft de vervagingsstraal terug of stelt deze in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


Bepaalt of de grenzen van het object moeten worden uitgebreid als gevolg van de vervaging. True geeft aan dat de grenzen worden uitgebreid terwijl false aangeeft dat dat niet het geval is. Lezen/Schrijven boolean.

**Retour:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


Bepaalt of de grenzen van het object moeten worden uitgebreid als gevolg van de vervaging. True geeft aan dat de grenzen worden uitgebreid terwijl false aangeeft dat dat niet het geval is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


Haalt effectieve Blur effectgegevens op met de erfenis toegepast.

**Retour:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - Een [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of de opgegeven [Blur](../../com.aspose.slides/blur) gelijk is aan de huidige [Blur](../../com.aspose.slides/blur).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [Blur](../../com.aspose.slides/blur) om te vergelijken. |

**Retour:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als hash-functie voor een bepaald type.

**Retour:**
int - Een hashcode voor het huidige object.