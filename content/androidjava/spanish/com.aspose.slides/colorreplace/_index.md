---
title: ColorReplace
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un efecto de reemplazo de color.
type: docs
url: /es/com.aspose.slides/colorreplace/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas las interfaces implementadas:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Representa un efecto de reemplazo de color. Todos los colores del efecto se cambian a un color fijo. Los valores alfa no se ven afectados.
## Métodos

| Método | Descripción |
| --- | --- |
| [getColor()](#getColor--) | Devuelve el formato de color que reemplazará el color de cada píxel. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto Color Replacement con la herencia aplicada. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [ColorReplace](../../com.aspose.slides/colorreplace) especificado es igual al [ColorReplace](../../com.aspose.slides/colorreplace) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Devuelve el formato de color que reemplazará el color de cada píxel. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Obtiene los datos efectivos del efecto Color Replacement con la herencia aplicada.

**Devuelve:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - Un [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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

Determina si el [ColorReplace](../../com.aspose.slides/colorreplace) especificado es igual al [ColorReplace](../../com.aspose.slides/colorreplace) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [ColorReplace](../../com.aspose.slides/colorreplace) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.