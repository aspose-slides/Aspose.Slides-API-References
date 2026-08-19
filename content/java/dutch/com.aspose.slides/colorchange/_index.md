---
title: ColorChange
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een Color Change-effect voor.
type: docs
url: /nl/com.aspose.slides/colorchange/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Stelt een Color Change-effect voor. Instanties van FromColor worden vervangen door instanties van ToColor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFromColor()](#getFromColor--) | Kleur die zal worden vervangen. |
| [getToColor()](#getToColor--) | Kleur die zal vervangen. |
| [getEffective()](#getEffective--) | Haalt effectieve gegevens van het Color Change-effect op met de overerving toegepast. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [ColorChange](../../com.aspose.slides/colorchange) gelijk is aan de huidige [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Dient als hash-functie voor een bepaald type. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

Kleur die zal worden vervangen. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

Kleur die zal vervangen. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Haalt effectieve gegevens van het Color Change-effect op met de overerving toegepast.

**Retourneert:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retourneert:**
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

**Retourneert:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als hash-functie voor een bepaald type.

**Retourneert:**
int - Een hashcode voor het huidige object.