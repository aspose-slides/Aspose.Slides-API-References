---
title: BiLevel
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa un efecto binario negro/blanco.
type: docs
url: /es/com.aspose.slides/bilevel/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas las interfaces implementadas:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Representa un efecto de nivel binario (negro/blanco). Los colores de entrada cuya luminancia es menor que el valor umbral especificado se cambian a negro. Los colores de entrada cuya luminancia es mayor o igual al valor especificado se establecen a blanco. Los valores de efecto alfa no se ven afectados por este efecto.

## Métodos

| Método | Descripción |
| --- | --- |
| [getEffective()](#getEffective--) | Obtiene los datos del efecto Bi-Level efectivos con la herencia aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [BiLevel](../../com.aspose.slides/bilevel) especificado es igual al [BiLevel](../../com.aspose.slides/bilevel) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Obtiene los datos del efecto Bi-Level efectivos con la herencia aplicada.

**Devuelve:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Un [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina si el [BiLevel](../../com.aspose.slides/bilevel) especificado es igual al [BiLevel](../../com.aspose.slides/bilevel) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [BiLevel](../../com.aspose.slides/bilevel) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.