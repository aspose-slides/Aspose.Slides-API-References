---
title: IAlphaBiLevel
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Alpha Bi-Level Effekt dar.
type: docs
url: /de/com.aspose.slides/ialphabilevel/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Stellt einen Alpha-Bi-Level-Effekt dar. Alpha-(Deckkraft)-Werte, die kleiner als der Schwellenwert sind, werden auf 0 (vollständig transparent) gesetzt und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden auf 100 % (vollständig undurchsichtig) gesetzt.

--------------------

Verwenden Sie ImageTransformOperationFactory, um Instanzen in COM zu erstellen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getThreshold()](#getThreshold--) | Gibt den Effekt-Schwellenwert zurück. |
| [setThreshold(float value)](#setThreshold-float-) | Gibt den Effekt-Schwellenwert zurück. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Gibt den Effekt-Schwellenwert zurück. Lese-/Schreib float.

**Rückgabewert:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Gibt den Effekt-Schwellenwert zurück. Lese-/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |