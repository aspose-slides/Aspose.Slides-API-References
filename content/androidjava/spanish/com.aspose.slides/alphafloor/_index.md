---
title: AlphaFloor
second_title: Aspose.Slides para Android a través de la referencia de la API Java
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

Representa un efecto Alpha Floor. Los valores Alpha (opacidad) menores al 100 % se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve completamente transparente.

## Métodos

| Método | Descripción |
| --- | --- |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto Alpha Floor con la herencia aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [AlphaFloor](../../com.aspose.slides/alphafloor) especificado es igual al [AlphaFloor](../../com.aspose.slides/alphafloor) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

Obtiene los datos efectivos del efecto Alpha Floor con la herencia aplicada.

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
| obj | java.lang.Object | El [AlphaFloor](../../com.aspose.slides/alphafloor) para comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.