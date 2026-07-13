---
title: IAlphaBiLevel
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un effetto Alpha a due livelli.
type: docs
url: /it/com.aspose.slides/ialphabilevel/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Rappresenta un effetto Alpha a due livelli. I valori Alpha (Opacity) inferiori alla soglia vengono modificati a 0 (completamente trasparente) e i valori Alpha maggiori o uguali alla soglia vengono modificati al 100% (completamente opaco).

--------------------

Usa ImageTransformOperationFactory per creare istanze in COM.
## Metodi

| Metodo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |