---
title: ColorReplace
second_title: Aspose.Slides voor Java API Referentie
description: Geeft een Color Replacement-effect weer.
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

Geeft een Color Replacement-effect weer. Alle effectkleuren worden gewijzigd naar een vaste kleur. Alfa-waarden blijven onaangetast.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColor()](#getColor--) | Retourneert het kleurformaat dat de kleur van elk pixel zal vervangen. |
| [getEffective()](#getEffective--) | Haalt de effectieve Color Replacement-effectgegevens op met de toegepaste erfenis. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [ColorReplace](../../com.aspose.slides/colorreplace) gelijk is aan de huidige [ColorReplace](../../com.aspose.slides/colorreplace). |
| [hashCode()](#hashCode--) | Dient als een hash-functie voor een bepaald type. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Retourneert het kleurformaat dat de kleur van elk pixel zal vervangen. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


Haalt de effectieve Color Replacement-effectgegevens op met de toegepaste erfenis.

**Retour:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - Een [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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


Bepaalt of de opgegeven [ColorReplace](../../com.aspose.slides/colorreplace) gelijk is aan de huidige [ColorReplace](../../com.aspose.slides/colorreplace).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [ColorReplace](../../com.aspose.slides/colorreplace) om te vergelijken. |

**Retour:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als een hash-functie voor een bepaald type.

**Retour:**
int - Een hash-code voor het huidige object.