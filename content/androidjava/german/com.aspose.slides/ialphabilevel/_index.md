---
title: IAlphaBiLevel
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt einen Alpha-Bi-Level-Effekt dar.
type: docs
url: /de/com.aspose.slides/ialphabilevel/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Stellt einen Alpha-Bi-Level-Effekt dar. Alpha (Opacity)-Werte, die kleiner als der Schwellenwert sind, werden zu 0 (vollständig transparent) geändert, und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden zu 100 % (vollständig undurchsichtig) geändert.

--------------------

Verwenden Sie ImageTransformOperationFactory, um Instanzen in COM zu erstellen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getThreshold()](#getThreshold--) | Gibt den Effekt-Schwellwert zurück. |
| [setThreshold(float value)](#setThreshold-float-) | Gibt den Effekt-Schwellwert zurück. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Gibt den Effekt-Schwellwert zurück. Lese-/Schreib-float.

**Rückgabewert:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Gibt den Effekt-Schwellwert zurück. Lese-/Schreib-float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |