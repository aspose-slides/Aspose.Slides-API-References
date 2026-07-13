---
title: ColorReplace
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Kleurvervangings-effect voor.
type: docs
url: /nl/com.aspose.slides/colorreplace/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Stelt een Kleurvervangings-effect voor. Alle effectkleuren worden gewijzigd naar een vaste kleur. Alfa-waarden blijven onaangetast.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColor()](#getColor--) | Retourneert het kleurenformaat dat de kleur van elke pixel zal vervangen. |
| [getEffective()](#getEffective--) | Haalt de effectieve Color Replacement-effectgegevens op met de overerving toegepast. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [ColorReplace](../../com.aspose.slides/colorreplace) gelijk is aan de huidige [ColorReplace](../../com.aspose.slides/colorreplace). |
| [hashCode()](#hashCode--) | Dient als hash-functie voor een bepaald type. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Retourneert het kleurenformaat dat de kleur van elke pixel zal vervangen. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


Haalt de effectieve Color Replacement-effectgegevens op met de overerving toegepast.

**Retourneert:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - Een [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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


Bepaalt of de opgegeven [ColorReplace](../../com.aspose.slides/colorreplace) gelijk is aan de huidige [ColorReplace](../../com.aspose.slides/colorreplace).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [ColorReplace](../../com.aspose.slides/colorreplace) om te vergelijken. |

**Retourneert:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als hash-functie voor een bepaald type.

**Retourneert:**
int - Een hashcode voor het huidige object.