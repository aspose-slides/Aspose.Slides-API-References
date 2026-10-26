---
title: IBlur
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa un efecto de desenfoque que se aplica a toda la forma, incluido su relleno.
type: docs
url: /es/com.aspose.slides/iblur/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Representa un efecto de desenfoque que se aplica a toda la forma, incluida su relleno. Todos los canales de color, incluido el alfa, se ven afectados.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRadius()](#getRadius--) | Returns or sets blur radius. |
| [setRadius(double value)](#setRadius-double-) | Returns or sets blur radius. |
| [getGrow()](#getGrow--) | Determines whether the bounds of the object should be grown as a result of the blurring. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determines whether the bounds of the object should be grown as a result of the blurring. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Devuelve o establece el radio del desenfoque. Lectura/escritura double.

**Devuelve:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Devuelve o establece el radio del desenfoque. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Determina si los límites del objeto deben expandirse como resultado del desenfoque. True indica que los límites se expanden mientras que false indica que no lo hacen. Lectura/escritura boolean.

**Devuelve:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Determina si los límites del objeto deben expandirse como resultado del desenfoque. True indica que los límites se expanden mientras que false indica que no lo hacen. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |