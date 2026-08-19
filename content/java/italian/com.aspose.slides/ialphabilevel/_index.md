---
title: IAlphaBiLevel
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un effetto Alpha a due livelli.
type: docs
url: /it/com.aspose.slides/ialphabilevel/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Rappresenta un effetto Alpha a due livelli. I valori Alpha (Opacità) inferiori alla soglia vengono modificati a 0 (completamente trasparente) e i valori alpha maggiori o uguali alla soglia vengono modificati al 100 % (completamente opaco).

--------------------

Usa ImageTransformOperationFactory per creare istanze in COM.
## Metodi

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Restituisce la soglia dell'effetto. |
| [setThreshold(float value)](#setThreshold-float-) | Restituisce la soglia dell'effetto. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Restituisce la soglia dell'effetto. Lettura/scrittura float.

**Restituisce:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Restituisce la soglia dell'effetto. Lettura/scrittura float.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |