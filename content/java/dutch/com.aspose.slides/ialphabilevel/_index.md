---
title: IAlphaBiLevel
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een Alpha Bi-Level effect voor.
type: docs
url: /nl/com.aspose.slides/ialphabilevel/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Stelt een Alpha Bi-Level effect voor. Alpha (opaciteit) waarden kleiner dan de drempel worden gewijzigd naar 0 (volledig transparant) en alfa-waarden die groter dan of gelijk aan de drempel zijn, worden gewijzigd naar 100% (volledig ondoorzichtig).

--------------------

Gebruik ImageTransformOperationFactory om instanties te maken in COM.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getThreshold()](#getThreshold--) | Retourneert de effectdrempel. |
| [setThreshold(float value)](#setThreshold-float-) | Retourneert de effectdrempel. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Retourneert de effectdrempel. Lezen/Schrijven float.

**Retour:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

Retourneert de effectdrempel. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |