---
title: Blur
second_title: Aspose.Slides para Android mediante la API Java
description: Representa un efecto Blur que se aplica a toda la forma, incluido su relleno.
type: docs
url: /es/com.aspose.slides/blur/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas las interfaces implementadas:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Representa un efecto Blur que se aplica a toda la forma, incluido su relleno. Todos los canales de color, incluido el alfa, se ven afectados.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRadius()](#getRadius--) | Devuelve o establece el radio de desenfoque. |
| [setRadius(double value)](#setRadius-double-) | Devuelve o establece el radio de desenfoque. |
| [getGrow()](#getGrow--) | Determina si los límites del objeto deben ampliarse como resultado del desenfoque. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determina si los límites del objeto deben ampliarse como resultado del desenfoque. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto Blur con la herencia aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [Blur](../../com.aspose.slides/blur) especificado es igual al [Blur](../../com.aspose.slides/blur) actual. |
| [hashCode()](#hashCode--) | Funciona como una función hash para un tipo particular. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Devuelve o establece el radio de desenfoque. Lectura/escritura double.

**Devuelve:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Devuelve o establece el radio de desenfoque. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Determina si los límites del objeto deben ampliarse como resultado del desenfoque. true indica que los límites se amplían mientras que false indica que no lo hacen. Lectura/escritura boolean.

**Devuelve:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Determina si los límites del objeto deben ampliarse como resultado del desenfoque. true indica que los límites se amplían mientras que false indica que no lo hacen. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Obtiene los datos efectivos del efecto Blur con la herencia aplicada.

**Devuelve:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - Un [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina si el [Blur](../../com.aspose.slides/blur) especificado es igual al [Blur](../../com.aspose.slides/blur) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [Blur](../../com.aspose.slides/blur) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Funciona como una función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.