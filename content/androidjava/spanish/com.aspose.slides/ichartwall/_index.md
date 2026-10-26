---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: Represents walls on 3d charts.
type: docs
url: /es/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Representa paredes en gráficos 3D.
## Métodos

| Método | Descripción |
| --- | --- |
| [getThickness()](#getThickness--) | Devuelve o establece el grosor de las paredes como un porcentaje de la mayor dimensión del volumen del trazado. |
| [setThickness(int value)](#setThickness-int-) | Devuelve o establece el grosor de las paredes como un porcentaje de la mayor dimensión del volumen del trazado. |
| [getFormat()](#getFormat--) | Devuelve el relleno, línea, efecto y estilos 3D de la pared. |
| [getPictureType()](#getPictureType--) | Devuelve o establece el tipo de imagen. |
| [setPictureType(int value)](#setPictureType-int-) | Devuelve o establece el tipo de imagen. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


Devuelve o establece el grosor de las paredes como un porcentaje de la mayor dimensión del volumen del trazado. Lectura/escritura int.

**Devuelve:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


Devuelve o establece el grosor de las paredes como un porcentaje de la mayor dimensión del volumen del trazado. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Devuelve el relleno, línea, efecto y estilos 3D de la pared. Solo lectura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```


Devuelve o establece el tipo de imagen. Lectura/escritura [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Devuelve:**
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