---
title: Backdrop3DScene
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Define un plano en el que se aplican efectos como resplandor y sombra en relación con la forma a la que se aplican.
type: docs
url: /es/com.aspose.slides/backdrop3dscene/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Define un plano en el que se aplican efectos, como resplandor y sombra, en relación con la forma a la que se aplican.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Devuelve o establece un vector normal. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Devuelve o establece un vector normal. |
| [getAnchorPoint()](#getAnchorPoint--) | Devuelve o establece un punto en el espacio 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Devuelve o establece un punto en el espacio 3D. |
| [getUpVector()](#getUpVector--) | Devuelve o establece un vector que representa la dirección arriba. |
| [setUpVector(float[] value)](#setUpVector-float---) | Devuelve o establece un vector que representa la dirección arriba. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Long de solo lectura.

**Devuelve:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Devuelve o establece un vector normal. Para ser más preciso, este atributo define un vector normal a la cara del plano de fondo. Vector representado por un array de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Devuelve:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Devuelve o establece un vector normal. Para ser más preciso, este atributo define un vector normal a la cara del plano de fondo. Vector representado por un array de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Devuelve o establece un punto en el espacio 3D. Este punto es el punto en el espacio que ancla el plano de fondo. Punto 3D representado por un array de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Devuelve:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Devuelve o establece un punto en el espacio 3D. Este punto es el punto en el espacio que ancla el plano de fondo. Punto 3D representado por un array de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Devuelve o establece un vector que representa la dirección arriba. Para ser más preciso, este atributo define un vector que representa la dirección arriba en relación con la cara del plano de fondo. Vector representado por un array de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Devuelve:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Devuelve o establece un vector que representa la dirección arriba. Para ser más preciso, este atributo define un vector que representa la dirección arriba en relación con la cara del plano de fondo. Vector representado por un array de 3 valores float que definen las coordenadas X, Y y Z. Lectura/escritura float[].

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float[] |  |