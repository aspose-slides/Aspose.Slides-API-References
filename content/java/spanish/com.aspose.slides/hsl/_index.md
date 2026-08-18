---
title: HSL
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un efecto de tono/saturación/luminancia.
type: docs
url: /es/com.aspose.slides/hsl/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas las interfaces implementadas:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Representa un efecto de tono/saturación/luminancia. El tono, la saturación y la luminancia pueden ajustarse individualmente respecto a su valor actual.
## Métodos

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto de tono/saturación/luminancia con la herencia aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [HSL](../../com.aspose.slides/hsl) especificado es igual al [HSL](../../com.aspose.slides/hsl) actual. |
| [hashCode()](#hashCode--) | Actúa como una función hash para un tipo particular. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```


Obtiene los datos efectivos del efecto de tono/saturación/luminancia con la herencia aplicada.

**Devuelve:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - Un [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el [HSL](../../com.aspose.slides/hsl) especificado es igual al [HSL](../../com.aspose.slides/hsl) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [HSL](../../com.aspose.slides/hsl) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Actúa como una función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.