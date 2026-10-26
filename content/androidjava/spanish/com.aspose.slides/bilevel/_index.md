---
title: BiLevel
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa un efecto Bi-Level blanco/negro.
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

Representa un efecto Bi-Level (blanco/negro). Los colores de entrada cuya luminancia es menor que el valor de umbral especificado se cambian a negro. Los colores de entrada cuya luminancia es mayor o igual al valor especificado se establecen a blanco. Los valores de efecto alfa no se ven afectados por este efecto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto Bi-Level con la herencia aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [BiLevel](../../com.aspose.slides/bilevel) especificado es igual al [BiLevel](../../com.aspose.slides/bilevel) actual. |
| [hashCode()](#hashCode--) | Funciona como una función hash para un tipo particular. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


Obtiene los datos efectivos del efecto Bi-Level con la herencia aplicada.

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
| obj | java.lang.Object | El [BiLevel](../../com.aspose.slides/bilevel) para comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funciona como una función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.