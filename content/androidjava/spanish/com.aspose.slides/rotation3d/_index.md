---
title: Rotation3D
second_title: Aspose.Slides para Android vía referencia de API Java
description: Representa la rotación 3D de un gráfico.
type: docs
url: /es/com.aspose.slides/rotation3d/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Representa la rotación 3D de un gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRotationX()](#getRotationX--) | Obtiene o establece el grado de rotación alrededor del eje X, es decir |
| [setRotationX(byte value)](#setRotationX-byte-) | Obtiene o establece el grado de rotación alrededor del eje X, es decir |
| [getRotationY()](#getRotationY--) | Obtiene o establece el grado de rotación alrededor del eje Y, es decir |
| [setRotationY(int value)](#setRotationY-int-) | Obtiene o establece el grado de rotación alrededor del eje Y, es decir |
| [getPerspective()](#getPerspective--) | Obtiene o establece el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Obtiene o establece el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Determina si los ejes del gráfico forman ángulos rectos, en lugar de dibujarse en perspectiva. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Determina si los ejes del gráfico forman ángulos rectos, en lugar de dibujarse en perspectiva. |
| [getDepthPercents()](#getDepthPercents--) | Obtiene o establece la profundidad de un gráfico 3D como porcentaje del ancho del gráfico (entre 20 y 2000 %). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Obtiene o establece la profundidad de un gráfico 3D como porcentaje del ancho del gráfico (entre 20 y 2000 %). |
| [getHeightPercents()](#getHeightPercents--) | Especifica la altura de un gráfico 3-D como porcentaje del ancho del gráfico (entre 5 y 500 %). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Especifica la altura de un gráfico 3-D como porcentaje del ancho del gráfico (entre 5 y 500 %). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```


Obtiene o establece el grado de rotación alrededor del eje X, es decir, en la dirección Y para gráficos 3D (entre -90 y 90 grados). La propiedad coincide con el elemento 21.2.2.157 rotX (X Rotation) en ECMA-376 y con la opción “Y Rotation” en PowerPoint 2007+. Lectura/escritura byte.

**Devuelve:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```


Obtiene o establece el grado de rotación alrededor del eje X, es decir, en la dirección Y para gráficos 3D (entre -90 y 90 grados). La propiedad coincide con el elemento 21.2.2.157 rotX (X Rotation) en ECMA-376 y con la opción “Y Rotation” en PowerPoint 2007+. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```


Obtiene o establece el grado de rotación alrededor del eje Y, es decir, en la dirección X para gráficos 3D (entre 0 y 360 grados). La propiedad coincide con el elemento 21.2.2.158 rotY (Y Rotation) en ECMA-376 y con la opción “X Rotation” en PowerPoint 2007+. Lectura/escritura int.

**Devuelve:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```


Obtiene o establece el grado de rotación alrededor del eje Y, es decir, en la dirección X para gráficos 3D (entre 0 y 360 grados). La propiedad coincide con el elemento 21.2.2.158 rotY (Y Rotation) en ECMA-376 y con la opción “X Rotation” en PowerPoint 2007+. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```


Obtiene o establece el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 240). Se ignora si el valor de la propiedad RightAngleAxes es true. Lectura/escritura byte.

**Devuelve:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```


Obtiene o establece el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 240). Se ignora si el valor de la propiedad RightAngleAxes es true. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```


Determina si los ejes del gráfico forman ángulos rectos, en lugar de dibujarse en perspectiva. En otras palabras, determina si los ángulos de los ejes son independientes de la rotación o elevación del gráfico. Lectura/escritura boolean.

**Devuelve:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```


Determina si los ejes del gráfico forman ángulos rectos, en lugar de dibujarse en perspectiva. En otras palabras, determina si los ángulos de los ejes son independientes de la rotación o elevación del gráfico. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```


Obtiene o establece la profundidad de un gráfico 3D como porcentaje del ancho del gráfico (entre 20 y 2000 %). Lectura/escritura int.

**Devuelve:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```


Obtiene o establece la profundidad de un gráfico 3D como porcentaje del ancho del gráfico (entre 20 y 2000 %). Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```


Especifica la altura de un gráfico 3-D como porcentaje del ancho del gráfico (entre 5 y 500 %). Lectura/escritura int.

**Devuelve:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```


Especifica la altura de un gráfico 3-D como porcentaje del ancho del gráfico (entre 5 y 500 %). Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject