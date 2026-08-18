---
title: ColorChange
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa un efecto de cambio de color.
type: docs
url: /es/com.aspose.slides/colorchange/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas las interfaces implementadas:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Representa un efecto de cambio de color. Las instancias de FromColor son reemplazadas por instancias de ToColor.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color que será reemplazado. |
| [getToColor()](#getToColor--) | Color que reemplazará. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto de cambio de color con la herencia aplicada. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [ColorChange](../../com.aspose.slides/colorchange) especificado es igual al [ColorChange](../../com.aspose.slides/colorchange) actual. |
| [hashCode()](#hashCode--) | Sirve como una función hash para un tipo particular. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

Color que será reemplazado. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

Color que reemplazará. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Obtiene los datos efectivos del efecto de cambio de color con la herencia aplicada.

**Devuelve:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - Un [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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

Determina si el [ColorChange](../../com.aspose.slides/colorchange) especificado es igual al [ColorChange](../../com.aspose.slides/colorchange) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [ColorChange](../../com.aspose.slides/colorchange) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como una función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.