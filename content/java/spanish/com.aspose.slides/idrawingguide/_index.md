---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Representa una guía de dibujo ajustable.
type: docs
url: /es/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Representa una guía de dibujo ajustable.
## Métodos

| Método | Descripción |
| --- | --- |
| [getOrientation()](#getOrientation--) | Devuelve o establece la orientación de la guía de dibujo. |
| [setOrientation(byte value)](#setOrientation-byte-) | Devuelve o establece la orientación de la guía de dibujo. |
| [getPosition()](#getPosition--) | Devuelve o establece la posición de la guía de dibujo en puntos desde la esquina superior izquierda de la diapositiva. |
| [setPosition(float value)](#setPosition-float-) | Devuelve o establece la posición de la guía de dibujo en puntos desde la esquina superior izquierda de la diapositiva. |
| [getColor()](#getColor--) | Devuelve o establece el color de la guía de dibujo. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Devuelve o establece el color de la guía de dibujo. |
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
public abstract Color getColor()
```


Devuelve o establece el color de la guía de dibujo. Lectura/escritura java.awt.Color.

**Devuelve:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Devuelve o establece el color de la guía de dibujo. Lectura/escritura java.awt.Color.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.Color |  |