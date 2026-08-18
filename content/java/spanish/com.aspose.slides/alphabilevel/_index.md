---
title: AlphaBiLevel
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un efecto Alpha Bi-Level.
type: docs
url: /es/com.aspose.slides/alphabilevel/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas las interfaces implementadas:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Representa un efecto Alpha Bi-Level. Los valores Alpha (Opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores alpha mayores o iguales al umbral se cambian a 100 % (totalmente opaco).
## Métodos

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Devuelve el umbral del efecto. |
| [setThreshold(float value)](#setThreshold-float-) | Devuelve el umbral del efecto. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto Alpha Bi-Level con la herencia aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [AlphaBiLevel](../../com.aspose.slides/alphabilevel) especificado es igual al [AlphaBiLevel](../../com.aspose.slides/alphabilevel) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Devuelve el umbral del efecto. Lectura/escritura float.

**Devuelve:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Devuelve el umbral del efecto. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Obtiene los datos efectivos del efecto Alpha Bi-Level con la herencia aplicada.

**Devuelve:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina si el [AlphaBiLevel](../../com.aspose.slides/alphabilevel) especificado es igual al [AlphaBiLevel](../../com.aspose.slides/alphabilevel) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [AlphaBiLevel](../../com.aspose.slides/alphabilevel) a comparar. |

**Devuelve:**
boolean - verdadero si los objetos son iguales; de lo contrario, falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.