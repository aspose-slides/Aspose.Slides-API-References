---
title: IChartWall
second_title: Referencia de API de Aspose.Slides para Java
description: Representa paredes en gráficos 3D.
type: docs
url: /es/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Representa paredes en gráficos 3D.
## Métodos

| Método | Descripción |
| --- | --- |
| [getThickness()](#getThickness--) | Returns or sets the walls thickness as a percentage of the largest dimension of the plot volume. |
| [setThickness(int value)](#setThickness-int-) | Returns or sets the walls thickness as a percentage of the largest dimension of the plot volume. |
| [getFormat()](#getFormat--) | Returns the wall fill, line, effect, 3d styles. |
| [getPictureType()](#getPictureType--) | Return or sets the picture type. |
| [setPictureType(int value)](#setPictureType-int-) | Return or sets the picture type. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

Devuelve o establece el espesor de las paredes como un porcentaje de la dimensión mayor del volumen del trazado. Lectura/escritura int.

**Returns:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

Devuelve o establece el espesor de las paredes como un porcentaje de la dimensión mayor del volumen del trazado. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Devuelve el relleno de la pared, la línea, el efecto, los estilos 3D. Solo lectura [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

Devuelve o establece el tipo de imagen. Lectura/escritura [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Returns:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

Devuelve o establece el tipo de imagen. Lectura/escritura [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |