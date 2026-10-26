---
title: AlphaBiLevel
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Alpha Bi-Level effect voor.
type: docs
url: /nl/com.aspose.slides/alphabilevel/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Stelt een Alpha Bi-Level effect voor. Alpha (Opacity) waarden kleiner dan de drempel worden gewijzigd naar 0 (volledig transparant) en alpha waarden groter dan of gelijk aan de drempel worden gewijzigd naar 100% (volledig ondoorzichtig).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getThreshold()](#getThreshold--) | Geeft de effectdrempel terug. |
| [setThreshold(float value)](#setThreshold-float-) | Geeft de effectdrempel terug. |
| [getEffective()](#getEffective--) | Haalt de effectieve Alpha Bi-Level effectgegevens op met de geërfde instellingen toegepast. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de gespecificeerde [AlphaBiLevel](../../com.aspose.slides/alphabilevel) gelijk is aan de huidige [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Dient als een hash-functie voor een bepaald type. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Geeft de effectdrempel terug. Lezen/Schrijven float.

**Retour:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Geeft de effectdrempel terug. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Haalt de effectieve Alpha Bi-Level effectgegevens op met de geërfde instellingen toegepast.

**Retour:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bepaalt of de gespecificeerde [AlphaBiLevel](../../com.aspose.slides/alphabilevel) gelijk is aan de huidige [AlphaBiLevel](../../com.aspose.slides/alphabilevel).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [AlphaBiLevel](../../com.aspose.slides/alphabilevel) om te vergelijken. |
**Retour:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als een hash-functie voor een bepaald type.

**Retour:**
int - Een hashcode voor het huidige object.