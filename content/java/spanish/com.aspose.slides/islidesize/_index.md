---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Representa el tamaño y la orientación de una diapositiva.
type: docs
url: /es/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Representa el tamaño y la orientación de una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSize()](#getSize--) | Obtiene las dimensiones de la diapositiva en puntos. |
| [getType()](#getType--) | Obtiene el tipo de tamaño de la diapositiva. |
| [getOrientation()](#getOrientation--) | Obtiene o establece la orientación de la diapositiva. |
| [setOrientation(int value)](#setOrientation-int-) | Obtiene o establece la orientación de la diapositiva. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Establece el tamaño de la diapositiva por tipo y escala el contenido existente. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Establece explícitamente las dimensiones de la diapositiva y escala el contenido existente. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Obtiene las dimensiones de la diapositiva en puntos.

--------------------

Asignar un nuevo valor restablece la propiedad \#getType.getType a [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) y establece \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Devuelve:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


Obtiene el tipo de tamaño de la diapositiva.

--------------------

Asignar cualquier valor distinto de [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajusta \#getSize.getSize según las dimensiones predefinidas, mientras se conserva la orientación actual \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Devuelve:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Obtiene o establece la orientación de la diapositiva.

--------------------

Cambiar este valor intercambia el ancho y la altura de la diapositiva.

**Devuelve:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Obtiene o establece la orientación de la diapositiva.

--------------------

Cambiar este valor intercambia el ancho y la altura de la diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Establece el tamaño de la diapositiva por tipo y escala el contenido existente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | El tamaño de diapositiva predefinido a aplicar. |
| scaleType | int | El modo de escalado del contenido a usar.

--------------------

Asignar cualquier valor distinto de [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajusta \#getSize.getSize según el tipo seleccionado, mientras se preserva \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Establece explícitamente las dimensiones de la diapositiva y escala el contenido existente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | float | El nuevo ancho de la diapositiva, en puntos. |
| height | float | El nuevo alto de la diapositiva, en puntos. |
| scaleType | int | El modo de escalado del contenido a usar.

--------------------

Esto restablece la propiedad \#getType.getType a [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) y establece el \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |