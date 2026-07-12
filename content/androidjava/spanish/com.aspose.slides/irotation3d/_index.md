---
title: IRotation3D
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa la rotación 3D de un gráfico.
type: docs
url: /es/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Representa la rotación 3D de un gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRotationX()](#getRotationX--) | Devuelve o establece el grado de rotación alrededor del eje X, es decir, |
| [setRotationX(byte value)](#setRotationX-byte-) | Devuelve o establece el grado de rotación alrededor del eje X, es decir, |
| [getRotationY()](#getRotationY--) | Devuelve o establece el grado de rotación alrededor del eje Y, es decir, |
| [setRotationY(int value)](#setRotationY-int-) | Devuelve o establece el grado de rotación alrededor del eje Y, es decir, |
| [getPerspective()](#getPerspective--) | Devuelve o establece el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Devuelve o establece el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Determina si los ejes del gráfico están en ángulos rectos, en lugar de dibujarse en perspectiva. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Determina si los ejes del gráfico están en ángulos rectos, en lugar de dibujarse en perspectiva. |
| [getDepthPercents()](#getDepthPercents--) | Devuelve o establece la profundidad de un gráfico 3D como porcentaje del ancho del gráfico (entre 20 y 2000 por ciento). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Devuelve o establece la profundidad de un gráfico 3D como porcentaje del ancho del gráfico (entre 20 y 2000 por ciento). |
| [getHeightPercents()](#getHeightPercents--) | Especifica la altura de un gráfico 3-D como porcentaje del ancho del gráfico (entre 5 y 500 por ciento). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Especifica la altura de un gráfico 3-D como porcentaje del ancho del gráfico (entre 5 y 500 por ciento). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Devuelve o establece el grado de rotación alrededor del eje X, es decir, en la dirección Y para gráficos 3D (entre -90 y 90 grados). La propiedad coincide con el elemento 21.2.2.157 rotX (X Rotation) en ECMA-376 y con la opción "Y Rotation" en PowerPoint 2007+. Lectura/escritura byte.

**Devuelve:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Devuelve o establece el grado de rotación alrededor del eje X, es decir, en la dirección Y para gráficos 3D (entre -90 y 90 grados). La propiedad coincide con el elemento 21.2.2.157 rotX (X Rotation) en ECMA-376 y con la opción "Y Rotation" en PowerPoint 2007+. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Devuelve o establece el grado de rotación alrededor del eje Y, es decir, en la dirección X para gráficos 3D (entre 0 y 360 grados). La propiedad coincide con el elemento 21.2.2.158 rotY (Y Rotation) en ECMA-376 y con la opción "X Rotation" en PowerPoint 2007+. Lectura/escritura int.

**Devuelve:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Devuelve o establece el grado de rotación alrededor del eje Y, es decir, en la dirección X para gráficos 3D (entre 0 y 360 grados). La propiedad coincide con el elemento 21.2.2.158 rotY (Y Rotation) en ECMA-376 y con la opción "X Rotation" en PowerPoint 2007+. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Devuelve o establece el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 100). Se ignora si el valor de la propiedad RightAngleAxes es verdadero. Lectura/escritura byte.

**Devuelve:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Devuelve o establece el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 100). Se ignora si el valor de la propiedad RightAngleAxes es verdadero. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Determina si los ejes del gráfico están en ángulos rectos, en lugar de dibujarse en perspectiva. En otras palabras, determina si los ángulos de los ejes del gráfico son independientes de la rotación o elevación del gráfico. Lectura/escritura boolean.

**Devuelve:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Determina si los ejes del gráfico están en ángulos rectos, en lugar de dibujarse en perspectiva. En otras palabras, determina si los ángulos de los ejes del gráfico son independientes de la rotación o elevación del gráfico. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Devuelve o establece la profundidad de un gráfico 3D como porcentaje del ancho del gráfico (entre 20 y 2000 por ciento). Lectura/escritura int.

**Devuelve:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Devuelve o establece la profundidad de un gráfico 3D como porcentaje del ancho del gráfico (entre 20 y 2000 por ciento). Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Especifica la altura de un gráfico 3-D como porcentaje del ancho del gráfico (entre 5 y 500 por ciento). Lectura/escritura int.

**Devuelve:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Especifica la altura de un gráfico 3-D como porcentaje del ancho del gráfico (entre 5 y 500 por ciento). Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |