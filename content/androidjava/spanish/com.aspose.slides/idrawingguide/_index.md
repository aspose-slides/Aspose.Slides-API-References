---
title: IDrawingGuide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an adjustable drawing guide.
type: docs
url: /es/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Represents an adjustable drawing guide.
## Métodos

| Método | Descripción |
| --- | --- |
| [getOrientation()](#getOrientation--) | Returns or sets orientation of the drawing guide. |
| [setOrientation(byte value)](#setOrientation-byte-) | Returns or sets orientation of the drawing guide. |
| [getPosition()](#getPosition--) | Returns or sets position of the drawing guide in points from the top, left corner of the slide. |
| [setPosition(float value)](#setPosition-float-) | Returns or sets position of the drawing guide in points from the top, left corner of the slide. |
| [getColor()](#getColor--) | Returns or sets color of the drawing guide. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Returns or sets color of the drawing guide. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


Devuelve o establece la orientación de la guía de dibujo. Lectura/escritura [Orientation](../../com.aspose.slides/orientation).

**Devuelve:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


Devuelve o establece la orientación de la guía de dibujo. Lectura/escritura [Orientation](../../com.aspose.slides/orientation).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Devuelve o establece la posición de la guía de dibujo en puntos desde la esquina superior izquierda de la diapositiva. Lectura/escritura float.

--------------------

El rango típico de valores es de cero a la altura de la diapositiva para una guía horizontal y de cero al ancho de la diapositiva para una guía vertical.

**Devuelve:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Devuelve o establece la posición de la guía de dibujo en puntos desde la esquina superior izquierda de la diapositiva. Lectura/escritura float.

--------------------

El rango típico de valores es de cero a la altura de la diapositiva para una guía horizontal y de cero al ancho de la diapositiva para una guía vertical.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```


Devuelve o establece el color de la guía de dibujo. Lectura/escritura java.lang.Integer.

**Devuelve:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


Devuelve o establece el color de la guía de dibujo. Lectura/escritura java.lang.Integer.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Integer |  |