---
title: IGlow
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un efecto de resplandor en el que se agrega un contorno borroso de color fuera de los bordes del objeto.
type: docs
url: /es/com.aspose.slides/iglow/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Representa un efecto de resplandor, en el que se agrega un contorno borroso de color fuera de los bordes del objeto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRadius()](#getRadius--) | Radio. |
| [setRadius(double value)](#setRadius-double-) | Radio. |
| [getColor()](#getColor--) | Formato de color. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Radio. Lectura/escritura double.

**Devuelve:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Radio. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Formato de color. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)