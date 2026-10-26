---
title: ColorChange
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een Color Change effect voor.
type: docs
url: /nl/com.aspose.slides/colorchange/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Stelt een Color Change effect voor. Instanties van FromColor worden vervangen door instanties van ToColor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFromColor()](#getFromColor--) | Kleur die vervangen zal worden. |
| [getToColor()](#getToColor--) | Kleur die zal vervangen. |
| [getEffective()](#getEffective--) | Haalt de effectieve Color Change effectgegevens op met de toegepaste overerving. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [ColorChange](../../com.aspose.slides/colorchange) gelijk is aan de huidige [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Dient als een hash-functie voor een bepaald type. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Kleur die vervangen zal worden. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Kleur die zal vervangen. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```


Haalt de effectieve Color Change effectgegevens op met de toegepaste overerving.

**Retour:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - Een [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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


Bepaalt of de opgegeven [ColorChange](../../com.aspose.slides/colorchange) gelijk is aan de huidige [ColorChange](../../com.aspose.slides/colorchange).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [ColorChange](../../com.aspose.slides/colorchange) om te vergelijken. |

**Retour:**
boolean - waar als objecten gelijk zijn; anders onwaar.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als een hash-functie voor een bepaald type.

**Retour:**
int - Een hashcode voor het huidige object.