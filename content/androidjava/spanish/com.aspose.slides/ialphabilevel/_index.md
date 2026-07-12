---
title: IAlphaBiLevel
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa un efecto alfa bi-nivel.
type: docs
url: /es/com.aspose.slides/ialphabilevel/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Representa un efecto alfa bi-nivel. Los valores alfa (opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores alfa mayores o iguales al umbral se cambian a 100 % (totalmente opaco).

--------------------

Use ImageTransformOperationFactory para crear instancias en COM.
## Métodos

| Método | Descripción |
| --- | --- |
| [getThreshold()](#getThreshold--) | Devuelve el umbral del efecto. |
| [setThreshold(float value)](#setThreshold-float-) | Devuelve el umbral del efecto. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Devuelve el umbral del efecto. Lectura/escritura float.

**Devuelve:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

Devuelve el umbral del efecto. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |