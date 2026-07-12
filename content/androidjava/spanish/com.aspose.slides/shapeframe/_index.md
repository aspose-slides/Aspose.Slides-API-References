---
title: ShapeFrame
second_title: Referencia de API de Aspose.Slides para Android a través de Java
description: Representa las propiedades de los marcos de forma.
type: docs
url: /es/com.aspose.slides/shapeframe/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Representa las propiedades del marco de forma.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Crea nuevas propiedades del marco de forma. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getX()](#getX--) | Devuelve la coordenada X de la esquina superior izquierda de un marco. |
| [getY()](#getY--) | Devuelve la coordenada Y de la esquina superior izquierda de un marco. |
| [getWidth()](#getWidth--) | Devuelve el ancho de un marco. |
| [getHeight()](#getHeight--) | Devuelve la altura de un marco. |
| [getRotation()](#getRotation--) | Devuelve el número de grados que el marco está rotado alrededor del eje z. |
| [getCenterX()](#getCenterX--) | Devuelve la coordenada X del centro del marco. |
| [getCenterY()](#getCenterY--) | Devuelve la coordenada Y del centro del marco. |
| [getFlipH()](#getFlipH--) | Determina si el marco está volteado horizontalmente. |
| [getFlipV()](#getFlipV--) | Determina si el marco está volteado verticalmente. |
| [getRectangle()](#getRectangle--) | Devuelve las coordenadas de un marco. |
| [deepClone()](#deepClone--) | Clona |
| [cloneT()](#cloneT--) | Clona. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un objeto especificado. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Devuelve un valor que indica si esta instancia es igual a un objeto especificado. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


Crea nuevas propiedades del marco de forma.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | Coordenada X de un marco. |
| y | float | Coordenada Y de un marco. |
| width | float | Ancho de un marco. |
| height | float | Altura de un marco. |
| flipH | byte | Verdadero si el marco está volteado horizontalmente. |
| flipV | byte | Verdadero si el marco está volteado verticalmente. |
| rotationAngle | float | Número de grados que el marco está rotado. |

### getX() {#getX--}
```
public final float getX()
```


Devuelve la coordenada X de la esquina superior izquierda de un marco. Solo lectura float.

**Devuelve:**
float
### getY() {#getY--}
```
public final float getY()
```


Devuelve la coordenada Y de la esquina superior izquierda de un marco. Solo lectura float.

**Devuelve:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Devuelve el ancho de un marco. Solo lectura float.

**Devuelve:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Devuelve la altura de un marco. Solo lectura float.

**Devuelve:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```


Devuelve el número de grados que el marco está rotado alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Solo lectura float.

**Devuelve:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Devuelve la coordenada X del centro del marco. Solo lectura float.

**Devuelve:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Devuelve la coordenada Y del centro del marco. Solo lectura float.

**Devuelve:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


Determina si el marco está volteado horizontalmente. Solo lectura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


Determina si el marco está volteado verticalmente. Solo lectura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```


Devuelve las coordenadas de un marco. Solo lectura android.graphics.RectF.

**Devuelve:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clona

**Devuelve:**
java.lang.Object - Cloned shape frame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


Clona.

**Devuelve:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Cloned shape frame.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Devuelve:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un objeto especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto con el que comparar esta instancia. |

**Devuelve:**
boolean - **true** si obj es un ShapeFrame que tiene el mismo valor que esta instancia; de lo contrario, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```


Devuelve un valor que indica si esta instancia es igual a un objeto especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | El ShapeFRameEx con el que comparar esta instancia. |

**Devuelve:**
boolean - **true** si value es un ShapeFrame que tiene el mismo valor que esta instancia; de lo contrario, **false**.