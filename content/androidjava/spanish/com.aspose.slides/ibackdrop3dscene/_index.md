---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /es/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Define un plano en el que los efectos, como el resplandor y la sombra, se aplican en relación con la forma a la que se aplican.
## Métodos

| Método | Descripción |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Devuelve o establece un vector normal. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Devuelve o establece un vector normal. |
| [getAnchorPoint()](#getAnchorPoint--) | Devuelve o establece un punto en el espacio 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Devuelve o establece un punto en el espacio 3D. |
| [getUpVector()](#getUpVector--) | Devuelve o establece un vector que representa la dirección arriba. |
| [setUpVector(float[] value)](#setUpVector-float---) | Devuelve o establece un vector que representa la dirección arriba. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


Devuelve o establece un vector normal. Para ser más preciso, este atributo define un vector normal a la cara del plano de fondo. Vector representado por una matriz de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Devuelve:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


Devuelve o establece un vector normal. Para ser más preciso, este atributo define un vector normal a la cara del plano de fondo. Vector representado por una matriz de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


Devuelve o establece un punto en el espacio 3D. Este punto es el punto en el espacio que ancla el plano de fondo. Punto 3D representado por una matriz de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Devuelve:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


Devuelve o establece un punto en el espacio 3D. Este punto es el punto en el espacio que ancla el plano de fondo. Punto 3D representado por una matriz de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


Devuelve o establece un vector que representa la dirección arriba. Para ser más preciso, este atributo define un vector que representa la dirección arriba en relación con la cara del plano de fondo. Vector representado por una matriz de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Devuelve:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


Devuelve o establece un vector que representa la dirección arriba. Para ser más preciso, este atributo define un vector que representa la dirección arriba en relación con la cara del plano de fondo. Vector representado por una matriz de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float[] |  |