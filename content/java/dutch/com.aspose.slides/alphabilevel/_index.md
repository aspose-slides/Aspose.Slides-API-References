---
title: AlphaBiLevel
second_title: Aspose.Slides voor Java API Referentie
description: Representeert een Alpha Bi-Level effect.
type: docs
url: /nl/com.aspose.slides/alphabilevel/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Representeert een Alpha Bi-Level effect. Alpha (Opacity) waarden lager dan de drempel worden gewijzigd naar 0 (volledig transparant) en alpha waarden groter dan of gelijk aan de drempel worden gewijzigd naar 100% (volledig ondoorzichtig).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getThreshold()](#getThreshold--) | Retourneert de effectdrempel. |
| [setThreshold(float value)](#setThreshold-float-) | Retourneert de effectdrempel. |
| [getEffective()](#getEffective--) | Haalt effectieve Alpha Bi-Level effectgegevens op met de overgeërfde waarden toegepast. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [AlphaBiLevel](../../com.aspose.slides/alphabilevel) gelijk is aan de huidige [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Dient als een hashfunctie voor een bepaald type. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Retourneert de effectdrempel. Lezen/Schrijven float.

**Retourneert:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


Retourneert de effectdrempel. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


Haalt effectieve Alpha Bi-Level effectgegevens op met de overgeërfde waarden toegepast.

**Retourneert:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - Een [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of de opgegeven [AlphaBiLevel](../../com.aspose.slides/alphabilevel) gelijk is aan de huidige [AlphaBiLevel](../../com.aspose.slides/alphabilevel).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | De [AlphaBiLevel](../../com.aspose.slides/alphabilevel) om te vergelijken. |

**Retourneert:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als een hashfunctie voor een bepaald type.

**Retourneert:**
int - Een hashcode voor het huidige object.