---
title: AlphaFloor
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un efecto Alpha Floor.
type: docs
url: /es/com.aspose.slides/alphafloor/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas las interfaces implementadas:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Representa un efecto Alpha Floor. Los valores de Alpha (opacidad) menores al 100% se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve totalmente transparente.
## Métodos

| Método | Descripción |
| --- | --- |
| [getEffective()](#getEffective--) | Obtiene los datos del efecto Alpha Floor efectivos con la herencia aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [AlphaFloor](../../com.aspose.slides/alphafloor) especificado es igual al [AlphaFloor](../../com.aspose.slides/alphafloor) actual. |
| [hashCode()](#hashCode--) | Funciona como una función hash para un tipo particular. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Obtiene los datos del efecto Alpha Floor efectivos con la herencia aplicada.

**Devuelve:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - Un [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el [AlphaFloor](../../com.aspose.slides/alphafloor) especificado es igual al [AlphaFloor](../../com.aspose.slides/alphafloor) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [AlphaFloor](../../com.aspose.slides/alphafloor) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funciona como una función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.