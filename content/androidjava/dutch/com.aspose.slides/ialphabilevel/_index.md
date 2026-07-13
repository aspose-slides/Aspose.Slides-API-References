---
title: IAlphaBiLevel
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Alpha Bi-Level effect voor.
type: docs
url: /nl/com.aspose.slides/ialphabilevel/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Stelt een Alpha Bi-Level effect voor. Alpha (Opaciteit) waarden die lager zijn dan de drempel worden gewijzigd naar 0 (volledig transparant) en alfade waarden die groter dan of gelijk aan de drempel zijn, worden gewijzigd naar 100% (volledig ondoorzichtig).

--------------------

Gebruik ImageTransformOperationFactory om instanties te maken in COM.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getThreshold()](#getThreshold--) | Retourneert effectdrempel. |
| [setThreshold(float value)](#setThreshold-float-) | Retourneert effectdrempel. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Retourneert effectdrempel. Lezen/schrijven float.

**Retourneert:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Retourneert effectdrempel. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |