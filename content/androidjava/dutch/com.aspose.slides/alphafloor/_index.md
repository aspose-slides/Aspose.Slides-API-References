---
title: AlphaFloor
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Alpha Floor effect voor.
type: docs
url: /nl/com.aspose.slides/alphafloor/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Stelt een Alpha Floor effect voor. Alpha (doorzichtigheid) waarden kleiner dan 100% worden op nul gezet. Met andere woorden, alles wat gedeeltelijk transparant is, wordt volledig transparant.
## Methoden

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Haalt de effectieve Alpha Floor effect-gegevens op met de erfenis toegepast. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [AlphaFloor](../../com.aspose.slides/alphafloor) gelijk is aan de huidige [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Dient als hash-functie voor een bepaald type. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Haalt de effectieve Alpha Floor effect-gegevens op met de erfenis toegepast.

**Retour:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - A [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of de opgegeven [AlphaFloor](../../com.aspose.slides/alphafloor) gelijk is aan de huidige [AlphaFloor](../../com.aspose.slides/alphafloor).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [AlphaFloor](../../com.aspose.slides/alphafloor) om te vergelijken. |

**Retour:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als hash-functie voor een bepaald type.

**Retour:**
int - Een hashcode voor het huidige object.