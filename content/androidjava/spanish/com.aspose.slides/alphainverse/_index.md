---
title: AlphaInverse
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa un efecto Alpha Inverse.
type: docs
url: /es/com.aspose.slides/alphainverse/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas las interfaces implementadas:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Representa un efecto Alpha Inverse. Los valores Alpha (opacidad) se invierten restando de 100%.

## Métodos

| Método | Descripción |
| --- | --- |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto Alpha Inverse con la herencia aplicada. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [AlphaInverse](../../com.aspose.slides/alphainverse) especificado es igual al [AlphaInverse](../../com.aspose.slides/alphainverse) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |

### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Obtiene los datos efectivos del efecto Alpha Inverse con la herencia aplicada.

**Devuelve:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - un [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina si el [AlphaInverse](../../com.aspose.slides/alphainverse) especificado es igual al [AlphaInverse](../../com.aspose.slides/alphainverse) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [AlphaInverse](../../com.aspose.slides/alphainverse) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.